# Traefik Deployment
**`Traefik Reverse Proxy Config`**

<hr>



<!-- ![Cover](deployment.drawio.png) -->

<!-- ## Demo Video

[![Demo Video](https://img.youtube.com/vi/8VNWsj8EbW/0.jpg)](https://www.youtube.com/watch?v=8VNWsj8EbW) -->


# 🚀 Usage

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



# 📝 Documentation

# 📚 References


# 🤝🏻 Connect with Me

[![GitHub](https://img.shields.io/badge/Github-%23222.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HuzaifaIrfan/)
[![Website](https://img.shields.io/badge/Website-%23222.svg?style=for-the-badge&logo=google-chrome&logoColor==%234285F4)](https://www.huzaifairfan.com)

# 📜 License

Licensed under the GPL3 License, Copyright 2025 Huzaifa Irfan. [LICENSE](LICENSE)
