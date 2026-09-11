# Prjs

Two self-contained applied-AI projects. Each directory is its own app with its
own spec, dependencies, and milestones — nothing is shared between them.

| Project | What it does | Status |
| --- | --- | --- |
| [`docintel/`](docintel/) | Extracts business documents into a validated schema, scores per-field confidence, routes uncertain fields to a human review queue. | Milestone 1 of 10 |
| [`voicedesk/`](voicedesk/) | AI phone receptionist: answers a business line, books appointments in a real calendar, escalates to a human when it should. | Not started |

Both use the same stack — Python 3.13, FastAPI, PostgreSQL, Alembic, psycopg 3,
SQLAlchemy 2.x — so setup is the same in either directory.

Each project's `README.md` is its spec: scope, non-goals, data model, and a
numbered milestone list. Build one milestone at a time; the non-goals and
"notes for the implementer" sections are the guardrails.
