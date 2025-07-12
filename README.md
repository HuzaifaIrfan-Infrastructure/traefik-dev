# traefik-dev

## create external network

```sh
docker network create web
```

## Setup le acme file

```sh
mkdir -p ./letsencrypt
touch ./letsencrypt/acme.json
chmod 600 ./letsencrypt/acme.json
```