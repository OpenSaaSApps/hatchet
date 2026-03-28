# CHANGES — Coolify-Compatible hatchet Deployment

## What Changed

Added `docker-compose.yaml` (Coolify-ready) alongside existing files.

- All configuration externalized as environment variables
- Required vars use `:?` fail-fast syntax
- Optional vars use `:-` with sensible defaults
- No hardcoded `container_name` (Coolify assigns its own)
- JSON logging with size limits on all services
- Health checks where applicable
- Full env var documentation in compose header
