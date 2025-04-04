# crewai-serper-agent

Researcher AI Agent built with CrewAI workflow using NeMo Guardrails

### DEVELOPMENT

Require:

*   `uv venv --python 3.13`
*   `uv tool install crewai`

Install:

```
$ uv init
$ uv venv
$ uv add ruff

$ uv run ruff format
$ uv run ruff check
add .pre-commit-config.yaml` then run `$ pre-commit install`

$ crewai install
```

Run:

```
$ crewai run
```