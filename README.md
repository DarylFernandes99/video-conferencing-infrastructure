# Meet Clone - Infrastructure

Infrastructure-as-Code (IaC) for the Meet Clone Project.
Contains Kubernetes manifests and Docker Compose configurations.

## Structure
- **docker-compose.yml**: Local development environment orchestration.

## Local Development (Docker Compose)
Runs the entire stack (Frontend, Backend, Redis, Postgres).

```bash
# Start all services
docker-compose up -d --build

# View logs
docker-compose logs -f
```