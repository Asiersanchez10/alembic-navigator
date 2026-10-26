# Alembic Navigator

**Alembic Navigator** is a plugin for JetBrains IDEs (PyCharm, IntelliJ IDEA and other IntelliJ-based IDEs, 2025.3+) that shows the
migration history of [Alembic](https://alembic.sqlalchemy.org/) (SQLAlchemy, FastAPI, Flask-Migrate…) inside the IDE and catches the
mistakes that usually break `alembic upgrade head` in CI: multiple heads, broken `down_revision` chains, duplicate revision ids and cycles.

- **JetBrains Marketplace:** coming soon.
- **License:** proprietary, see [EULA.md](EULA.md). The plugin's source code is not published in this repository.
- **Support and bug reports:** please open a [GitHub Issue](../../issues) in this repository.

The plugin reads your migration files locally and does not collect or send any data.
