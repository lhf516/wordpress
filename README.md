# Wordpress

Wordpress docker example

## Procedures to start the dockers
1. Manually create network `net-wordpress`
2. Copy `.env.sample` to `.env` and update the values as you want
3. Run `docker compose -f "docker/docker-compose.res.yml" up -d --build`
4. Then run `docker compose -f "docker/docker-compose.dev.yml" up -d --build`
5. Browse `http://localhost:[WP_PORT in .env]`, e.g. `http://localhost:3000` to start the wordpress configuration
