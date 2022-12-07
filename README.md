# kafka-playground
Local setup (single-node) via Docker


# Initialize

`docker-compose up -d`

## Checking that servers are listening on the ports specified

`nc -z localhost 29092`
`nc -z localhost 22181`

## Checking logs

`docker-compose logs kafka | grep -i started`
