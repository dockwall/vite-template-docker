# React + Vite + Docker CI/CD

I used a default Vite template (React) to study CI/CD using Docker

- `Dockerfile.dev` - config for the develop container (with HMR)

- `docker-compose-dev.yml` - config for extended usage in the development phase (HMR container + container with tests)

- `Dockerfile` - config for the production container (nginx + static files)
