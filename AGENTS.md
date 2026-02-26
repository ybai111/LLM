# AGENTS.md

## Cursor Cloud specific instructions

This is a freshly initialized repository titled "LLM" with no application code yet. The repo contains only a placeholder `README.md`.

- **No dependencies** to install — no `requirements.txt`, `pyproject.toml`, `package.json`, or any other dependency manifest exists.
- **No services** to run — no application entry points, no Docker configurations.
- **No tests** to execute — no test files or test frameworks configured.
- **No lint/build** — no linter or build tooling configured.

### User preferences (from workspace rules)

When code is added, the user prefers:
- Python 3.10+ with Poetry/Rye for dependency management
- Ruff for linting/formatting
- pytest for testing
- FastAPI for web APIs
- Type hints on all functions

### Terraform/IaC context

The workspace rules include a Terraform AWS architecture specification. Any Terraform code should follow the seven-layer directory structure documented in the workspace rules (`iac/terraform/{tenant}/{cloud}/{datacenter}/{account}/{region}/{service}/`).
