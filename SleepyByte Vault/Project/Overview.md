# SleepyByte 2.0

**Purpose:** local-first OSINT and cyber-intelligence workbench.

## Current repository

- Backend: FastAPI application in `main.py`.
- Existing application: Jinja template in `templates/index.html`.
- New modular interface: `SleepyByte Vault/frontend/`, available at `/workbench` when the server is running.
- License: MIT.

## Local development

Install the dependencies in `requirements.txt`, then start the app with `uvicorn main:app --reload`. Open `http://127.0.0.1:8000/workbench` for the new workbench and `/` for the existing interface.

## Product principles

- Keep investigations local by default.
- Make integration status explicit; never fabricate results.
- Preserve source, timestamp, and confidence for findings.
- Use external providers only when configured.
