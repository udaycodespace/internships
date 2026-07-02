# CI / CD — GitHub Actions example

This repository includes a simple GitHub Actions workflow at `.github/workflows/ci.yml` that demonstrates a practical CI pipeline for the project:

- `backend-test`: installs Node 20, runs `npm ci` and `npm test` inside `backend/`.
- `frontend-build`: installs Node 20, runs `npm ci` and `npm run build` inside `frontend/`.
- `docker-build`: (after tests and build) builds Docker images for `backend` and `frontend` using `docker/build-push-action` with `push: false`.

How to use

1. Push changes to `dev` or open a PR — workflow runs automatically.
2. Fix failing tests reported in the workflow; the `backend-test` job must pass before images are built.

Extending for a full CD
- To publish images to a registry, configure secrets (`DOCKERHUB_USERNAME`, `DOCKERHUB_TOKEN`, or GitHub Packages) and set `push: true` with `tags` in the `docker-build` job.
- For deploy stages, add a job to deploy to your environment (SSH, Kubernetes, or cloud provider) that depends on `docker-build`.

Security notes
- Store credentials in GitHub Actions Secrets, not in code.
- Limit which branches can trigger deploy workflows.
