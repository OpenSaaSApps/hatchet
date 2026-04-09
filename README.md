# hatchet

> Click To Deploy Hatchet — Workflow Orchestration Engine

[![Sync](https://github.com/opensaasapps/hatchet/actions/workflows/sync.yml/badge.svg)](https://github.com/opensaasapps/hatchet/actions/workflows/sync.yml) [![Docker](https://github.com/opensaasapps/hatchet/actions/workflows/docker.yml/badge.svg)](https://github.com/opensaasapps/hatchet/actions/workflows/docker.yml) [![Docker Pulls](https://img.shields.io/docker/pulls/thefractionalpm/hatchet)](https://hub.docker.com/r/thefractionalpm/hatchet)

Upstream: [hatchet-dev/hatchet](https://github.com/hatchet-dev/hatchet) · Auto-synced daily

---

## One-Command Deploy

```bash
cp .env.example .env && nano .env
docker compose up -d
```

## Coolify / Dokploy

1. New service → **Docker Compose**
2. Paste `docker-compose.yml`
3. Set env vars in UI
4. Deploy

## Environment Variables

| Variable | Required | Description |
|---|---|---|
| `DATABASE_URL` | ⚪ | |
| `SERVER_URL` | ⚪ | |
| `SERVER_AUTH_COOKIE_DOMAIN` | ⚪ | |
| `SERVER_AUTH_COOKIE_INSECURE` | ⚪ | |
| `SERVER_MSGQUEUE_KIND` | ⚪ | |
| `SERVER_PORT` | ⚪ | |
| `SERVER_GRPC_PORT` | ⚪ | |
| `SERVER_GRPC_BROADCAST_ADDRESS` | ⚪ | |

## Image

```
docker pull ghcr.io/hatchet-dev/hatchet/hatchet-engine:latest
docker pull thefractionalpm/hatchet:latest
```

## Ports

| Port | Service |
|---|---|
| `8080` | Main app |

---

*Part of the [OpenSaaSApps](https://github.com/opensaasapps) Click-To-Deploy collection.*
