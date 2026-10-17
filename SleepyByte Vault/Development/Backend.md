# Backend

The current backend is a FastAPI app in `main.py`, with Jinja templates under `templates/`. The pre-existing interface is served at `/`; the modular UI is served separately under `/workbench`.

The current backend does not yet expose the `/api/v1/health` endpoint described in the supplied UI draft. Dashboard status is therefore local placeholder content until an API contract is added.
