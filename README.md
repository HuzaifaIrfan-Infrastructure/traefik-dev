<div align="center">
  <h1>Traefik Deployment</h1>
  <h3 align="center"> Traefik Reverse Proxy Config  🚀</h3>
</div>


<!-- •[Upwork](https://www.upwork.com/jobs/~) -->

<hr>



<!-- ![Cover](deployment.drawio.png) -->

<!-- ## Demo Video

[![Demo Video](https://img.youtube.com/vi/8VNWsj8EbW/0.jpg)](https://www.youtube.com/watch?v=8VNWsj8EbW) -->


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



## 🤝🏻 &nbsp;Connect with Me

<p align="center">
<a href="https://www.huzaifairfan.com"><img src="https://img.shields.io/badge/-huzaifairfan.com-1aa260?style=flat&logo=Google-Chrome&logoColor=white"/></a>
<a href="https://github.com/HuzaifaIrfan/"><img src="https://img.shields.io/badge/-Github-4078c0?style=flat&logo=Github&logoColor=white"/></a>
<a href="mailto:hi@huzaifairfan.com"><img src="https://img.shields.io/badge/-hi@huzaifairfan.com-c71610?style=flat&logo=Gmail&logoColor=white"/></a>
<a href="https://www.upwork.com/freelancers/huzaifairfan2001"><img src="https://img.shields.io/badge/-Upwork-14a800?style=flat&logo=Upwork&logoColor=white"/></a>
</p>

## License

Licensed under the MIT License, Copyright 2025 Huzaifa Irfan. [LICENSE](LICENSE)