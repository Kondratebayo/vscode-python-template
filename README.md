# vscode-python-template

Personal VS Code + ruff config template for new Python projects. No `pyproject.toml` — that's created by `uv init`.

## Contents

- `.vscode/settings.json` — interpreter, ruff formatting, pytest, `src/` path analysis
- `.vscode/extensions.json` — recommended extensions
- `ruff.toml` — linting and formatting rules
- `.gitignore` — standard Python/uv ignores

## Usage

```bash
uv init my-new-project
```

Copy `.vscode/`, `ruff.toml`, and `.gitignore` from this template into the new project.
