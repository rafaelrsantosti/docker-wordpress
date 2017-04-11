## Instalação

Clona o repositorio:

```bash
$ git clone https://github.com/rafaelrsantosti/docker-wordpress.git
$ cd docker-wordpress
```

## Via imagem única

Cria imagem localmente e sobe o container:

```bash
$ docker build -t "rafaelrsantos/docker-wordpress:nginx" .
$ sudo docker run -p 80:80 --name docker-wordpress -d rafaelrsantos/docker-wordpress:nginx
```

Endereço de acesso:
```
http://127.0.0.1
```

## Via docker-compose

Sobe os serviços:

```bash
$ docker-compose up -d
```

Endereço de acesso:
```
http://127.0.0.1:8000
```

