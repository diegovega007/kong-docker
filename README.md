# kong-docker
docker compose up -d
KONG_DATABASE=postgres docker compose --profile database up -d
docker compose ps