# IHM Seascape

This repository supports data discovery and analysis related to the North Sea and the co-use of offshore wind farms. The working instructions for AI agents are in [`AGENTS.md`](AGENTS.md); consult them before starting a task.

## How to work with this repository

Depending on the request, the agent may:

- provide an overview of available data and tables;
- create a Jupyter notebook to answer a research question;
- give a brief answer grounded in available data.

Use only the permitted sources for data discovery and analysis, and follow the source-verification, privacy, and read-only requirements in `AGENTS.md`. Do not invent tables, columns, values, or results, and be clear about what could and could not be verified.

## Sources and reference material

Policy and reference material on the co-use of offshore wind farms is collected in [`references/medegebruik/`](references/medegebruik/). Its overview file links to the related policy and topic-specific documents.

## Project files

- `AGENTS.md` — working instructions for AI agents.
- `references/medegebruik/` — policy and reference material on offshore wind farm co-use.
- `notebooks/` — existing and newly generated Jupyter notebooks.

## Notebook deliverables

Notebooks are written in Dutch. They explain the research question, the sources and data used, the assumptions made, and the limitations. They also state honestly whether the notebook was executed and checked. See `AGENTS.md` for the full requirements.
