## Docker

    docker compose down
    docker compose up -d --build

## Check confign

    docker compose exec nginx nginx -T | sed -n '1,200p'

## Update
    
    docker compose exec nginx nginx -t
    docker compose exec nginx nginx -s reload
