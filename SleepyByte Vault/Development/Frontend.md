# Frontend

The modular UI lives under `SleepyByte Vault/frontend/` and is served by FastAPI at `/workbench`.

## Structure

- `index.html` — application shell
- `css/tokens.css` — palette and shared design values
- `css/base.css`, `layout.css`, `components.css`, `views.css` — styles by responsibility
- `js/app.js` — navigation, overview, settings, and command search

The UI is plain HTML, CSS, and JavaScript modules. Route hashes use paths such as `#/overview` and `#/tools/domain`. Module pages explain their purpose and implementation phase; the username page submits to the existing scanner. Other analysis modules need backend handlers before they can return live findings.
