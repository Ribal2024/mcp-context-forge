# Project Architecture

**Last Scanned:** 2026-07-11 | **Classification:** READY

ContextForge is a FastAPI MCP registry and gateway backed by PostgreSQL and Redis in its default Compose deployment. Nginx exposes the Admin UI and APIs on port 8080. The gateway federates registered MCP servers and applies authentication, visibility scoping, RBAC, audit, and plugin policies.
