# Senzing Boot Camp

This repository supports the Senzing Boot Camp — a two-day agentic programming workshop
where participants use AI to generate code and build assets using Senzing entity resolution.

## Repository Structure

- `docs/senzing-bootcamp-application.md` — Application guide and conversational questionnaire for prospective attendees
- `docs/business-questions.md` — Curated list of business questions answerable with Senzing, organized by use case
- `docs/todo.md` — Open tasks and action items for the project
- `README.md` — Project readme

## Key Context

- The application guide (`@docs/senzing-bootcamp-application.md`) defines a conversational flow for qualifying boot camp applicants. It is loaded as session context when Claude Code runs in this project.
- Business questions cover: identity resolution, fraud detection, KYC/compliance, watchlist screening, relationship discovery, risk assessment, operational intelligence, insider threat, and supply chain.
- Todos are tracked in `docs/todo.md`, not GitHub Issues.

## Conventions

- Commits use Conventional Commits format with `Co-Authored-By` trailer.
- Use the Senzing MCP server tools (`search_docs`, `get_sdk_reference`, etc.) for any Senzing-related questions rather than general knowledge.

@docs/senzing-bootcamp-application.md
