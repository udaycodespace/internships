# Docker — Run the project with containers

This repo includes Dockerfiles and a `docker-compose.yml` to run a local development-like environment: MongoDB, backend API, and frontend static site.

Files added
- `backend/Dockerfile` — Node image that runs `server.js`.
- `frontend/Dockerfile` — multi-stage build: Node builds Vite output, served by `nginx`.
- `docker-compose.yml` — brings up `mongo`, `backend`, and `frontend` services.

Quick start (Docker & Docker Compose installed)

```bash
# build and start all services
docker compose up --build

# stop
docker compose down
```

Notes
- The backend expects a Mongo connection string at `MONGO_URI`. `docker-compose.yml` points it at the `mongo` service.
- For production you should create a proper production-ready Dockerfile, set secrets via environment variables or a secrets manager, and use a registry to store images.

Debugging
- View backend logs: `docker compose logs -f backend`
- Run a shell in the backend image: `docker compose run --rm backend sh`

Security
- Do not commit real credentials into `.env` or `docker-compose.yml`. Use an `.env` file referenced by compose or your orchestration secrets.
