---
applyTo: "backend/**/*,*.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Log full error details on the server, and return standardized, sanitized error responses to the frontend (appropriate HTTP status and safe error code/message) without exposing stack traces or sensitive information.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If potential breaking changes are found, mention them to the developer.
