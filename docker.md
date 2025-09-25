# Topics to Learn for Docker

## 1. Docker Fundamentals

- What Docker is & why use it (containers vs VMs)
- Docker architecture (Client, Daemon, Registry, Images, Containers)
- Installation & setup on your OS (Windows, macOS, Linux)
- Core commands:
  - docker run, docker ps, docker stop, docker rm
  - docker exec, docker logs, docker inspect
  - Docker CLI vs Docker Desktop
- Port mapping (-p host:container)

## 2. Docker Images

- What images are & how they work
- Pulling images from Docker Hub
- Writing a Dockerfile (FROM, RUN, COPY, WORKDIR, CMD, ENTRYPOINT)
- Multi-stage builds (for smaller image size)
- Best practices for image optimization
- Using .dockerignore effectively
- Image tagging & versioning

## 3. Containers

- Creating, starting, stopping, and removing containers
- Detached vs interactive mode (-d, -it)
- Environment variables (-e and --env-file)
- Persisting container data

## 4. Networking in Docker

- Docker network types:
  - bridge
  - host
  - none
- custom user-defined networks

## 5. Data Management

- Volumes vs bind mounts
- Named volumes & anonymous volumes
- Sharing volumes between containers
- Backup & restore volumes

## 6. Docker Compose

- Why use docker-compose.yml
- Syntax & structure
- Running multiple services together
- Environment variables in Compose
- Using depends_on for service dependencies
- Scaling containers (docker compose up --scale)

## 7. Docker for Full-Stack Development

- Live reload setup for development
- Containerized MERN stack app
- Setting up reverse proxy with Nginx in Docker
- Docker Compose with Nginx reverse proxy + SSL
- Multi-stage build for a Next.js + Node API
- PostgreSQL database container with backups
- Development vs production Docker setup

## 8. Security & Best Practices

- Using official & minimal base images
- Managing secrets (Docker secrets, .env)
- Non-root user containers
- Scanning images for vulnerabilities
- Limiting container resources (--memory, --cpus)

## 9. Debugging & Monitoring

- Checking logs (docker logs)
- Container health checks
- Docker stats & monitoring tools

## 10. Advanced Topics

- Docker Swarm basics (intro to orchestration)
- Deploying to production with Docker
- Using private Docker registries
- Multi-architecture builds (x86, ARM)
- BuildKit & caching
- Automated builds with GitHub Actions / CI/CD
