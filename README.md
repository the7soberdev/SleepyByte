# SleepyByte

SleepyByte is a local-first OSINT and cyber-intelligence workbench. This repository contains the FastAPI application, its existing web interface, and a modular interface with project notes packaged as an Obsidian vault.

## What's inside

- `main.py` — FastAPI server and reconnaissance workflows
- `templates/` — existing server-rendered interface
- `SleepyByte Vault/frontend/` — modular SleepyByte 2.0 interface
- `SleepyByte Vault/` — Obsidian vault with project, development, and research notes

## Run locally

Use Python 3.10 or later. Install the application dependencies and start the server:

```bash
python -m pip install -r requirements.txt
uvicorn main:app --reload
```

Open <http://127.0.0.1:8000/> for the existing interface, or <http://127.0.0.1:8000/workbench> for the modular workbench.

The Obsidian vault is the `SleepyByte Vault/` directory. In Obsidian, choose **Open folder as vault** and select that directory. The frontend is also available as regular files in VS Code under `SleepyByte Vault/frontend/`.

## Status

The modular workbench currently provides navigation, overview, settings, and module placeholders. Connecting those views to a complete API is ongoing. The older interface remains at `/`.

## Privacy and responsible use

Use public data sources responsibly and follow applicable laws, provider terms, and rate limits. Do not commit API credentials, private investigation data, or collected personal data. Optional providers should be configured deliberately.

## License

MIT. See [LICENSE](LICENSE).
