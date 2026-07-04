# Learning Docker

How Docker is used in real projects?

Here's the roadmap I've planned to learn Docker:

| Step     | Topic                                | Status  |
| -------- | ------------------------------------ | ------- |
| ✅ 1      | Docker fundamentals                  | Done    |
| ✅ 2      | Images, layers, cache                | Done    |
| ✅ 3      | Containers and useful commands       | Done    |
| ✅ 4      | Volumes                              | Done    |
| ✅ 5      | Docker Compose basics                | Done    |
| ✅ 6      | PostgreSQL + Docker Compose + Django | Done    |
| ✅ 7      | Environment variables (`.env`)       | Done    |
| ✅ 8      | Production Dockerfile (Gunicorn)     | Done    |
| ✅ 9      | Nginx container                      | Done    |
| ✅ 10     | Static & media files                 | Done    |
| ✅ 11     | Deploy on a Linux VPS                | Done    |

---

# Next Steps

You've built a strong foundation. To deepen your Docker skills, I'd recommend learning these topics in order:

1. **Multi-stage Docker builds** (smaller, cleaner images)
2. **Health checks** (`HEALTHCHECK` and Compose healthchecks)
3. **Docker networking** in more depth
4. **Named volumes vs bind mounts** in production
5. **Redis** for caching and sessions
6. **Celery** for background tasks
7. **CI/CD** with GitHub Actions to build and deploy automatically
8. **Container registries** (such as GitHub Container Registry or Docker Hub)
9. **Basic Kubernetes** after you're comfortable with Docker Compose

<!-- 
| ✅ 8      | Production Dockerfile (Gunicorn)     | Done    |
| ✅ 9      | Nginx container                      | **Now** |
| **➡️ 10** | Static & media files                 | Next    |
| 11       | Docker networking in depth           | Later   |
| 12       | Deploy on a Linux VPS                | Final   |
 -->