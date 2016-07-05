## Instalação

Criar a imagem localmente:

```bash
$ git clone https://github.com/rafaelrsantosti/docker-wordpress.git
$ cd docker-wordpress
$ docker build -t "rafaelrsantos/docker-wordpress:nginx" .
```

## Executar o Container

```bash
$ sudo docker run -p 80:80 --name docker-wordpress -d rafaelrsantos/docker-wordpress:nginx
```

Endereço de acesso:
```
http://127.0.0.1:80
```
