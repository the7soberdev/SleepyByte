# Frontend

The modular UI lives under `SleepyByte Vault/frontend/` and is served by FastAPI at `/workbench`.

## Structure

- `index.html` — application shell
- `css/tokens.css` — palette and shared design values
- `css/base.css`, `layout.css`, `components.css`, `views.css` — styles by responsibility
- `js/app.js` — navigation, overview, settings, and command search

The UI is plain HTML, CSS, and JavaScript modules. Route hashes use paths such as `#/overview` and `#/tools/domain`. The module pages are UI placeholders until API handlers are connected.
