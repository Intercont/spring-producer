# Projeto RabbitMQ - Producer
##Comandos para o Docker
Para iniciar o Rabbit no Docker, usar a seguinte linha de comando
* docker run -d -p 15672:15672 -p 5672:5672 --name rabbitmq rabbitmq:3-management

Já irá baixar a imagem do rabbitmq e do gerenciador web do rabbit

Para acessar o terminal da imagem do rabbitMQ no Docker, executar o container de forma interativa com o comando abaixo
* docker exec -it rabbitmq bash


