# Project Goal

This project is a personal data-tracking and visualization system.

Primary objectives:
- Ingest monthly CSV exports from a mobile counting app
- Perform simple, deterministic ETL into DuckDB
- Provide interactive, local-first visualizations via Streamlit
- Remain simple, understandable, and easy to deploy
- Favor clarity and maintainability over premature abstraction

Non-goals:
- No real-time ingestion
- No distributed systems
- No complex auth, user management, or cloud infra (for now)

Design principles:
- Local-first and file-based
- Explicit schemas and transformations
- Minimal dependencies
- Easy to pivot later to a deployable demo
