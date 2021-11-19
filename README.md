# Posthog for "RxJS Debugging for Visual Studio Code"

> [Docker Compose](https://docs.docker.com/compose/) manifest to run a Posthog instance for [RxJS Debugging for Visual Studio Code](https://github.com/swissmanu/rxjs-debugging-for-vscode).

## Services

- Analytics: [Posthog](https://posthog.com/)
- Database: [PostgreSQL](https://www.postgresql.org/)
- Cache: [Redis](https://redis.io/)
- Reverse Proxy: [caddy-docker-proxy](https://github.com/lucaslorentz/caddy-docker-proxy)

## Usage

1. Copy `.env.example` to `.env`
2. Update `.env` with your specific configuration options
3. `docker compose up`
4. Posthog should be available on port `443`
