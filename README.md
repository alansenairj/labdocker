#Lab Docker

Lab 1,2,3, desafio 1 e 2 completados

Lab consiste em uma aplicação flask ligada a um banco redis que consegue registrar o número de visitas e também altera o texto do site recebendo uma variável. 

Estrutura se monta por um arquivo docker-compose.Ele importa as definições de um Dockerfile. 

Para ativar, basta digitar:
docker-compose up -d
*instalar o docker-compose antes - 
sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o && /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
