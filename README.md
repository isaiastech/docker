# docker
Aprendendo Docker

## Comandos docker

* docker ps "Ver os containers passa a flag -t para ver todos"
* rodar ubunto "docker run -it ubuntu"
* docker build -t app .  "Criando Imagem"
* docker build -t app:v1.0.0 .  "Criando Imagem colocando tag"
* docker images  "Ver imagens"
* docker run -it app sh "Abrindo imagen"
* RUN apk add --no-cache python2 g++ make "Instalando Python"
* docker run -dp 3000:3000 app
* docker volume create app-dados "Criar Volumes"
* docker volume inspect app-dados "Consultar Volumes"
* docker run -d -p 3000:3000 --name Kiwi -v app-dados:/app/dados 0b46006bb8f4 "Criando containe e ligando dados
* docker-compose up -d  "Iniciar container"
* docker-compose down  "Finaliza container"
 
## Comandos Linux

* whoami
* echo
* echo $0
* apt list
