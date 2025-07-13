# traefik-dev

## copy example configs
```sh
cp example.dynamic_conf.yml dynamic_conf.yml
cp example.traefik.yml traefik.yml
```

## create external network

```sh
docker network create web
```

## Setup le acme file

```sh
mkdir -p ./logs
mkdir -p ./letsencrypt
touch ./letsencrypt/acme.json
chmod 600 ./letsencrypt/acme.json
```

## mkcert

```sh
mkcert cattr.home git.home     
mkdir -p certs                                                 
mv cattr.home+1.pem certs/local.crt
mv cattr.home+1-key.pem certs/local.key
```