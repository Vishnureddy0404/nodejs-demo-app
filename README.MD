# Node.js Demo App with CI/CD

This is a sample Node.js web application deployed using a GitHub Actions CI/CD pipeline.

### Features:
- Dockerized Node.js App
- GitHub Actions pipeline: test → build → Docker push

### How it works:
- On push to `main`, the pipeline:
  1. Installs Node.js
  2. Runs tests
  3. Builds a Docker image
  4. Pushes to DockerHub

