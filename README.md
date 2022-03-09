
- para rodar na sua maquina:
#docker-compose build

#cp app/.env.example app/.env

- sobe o projeto
#docker-compose up

- entra no container
#docker-compose exec -it basesymfony_app_1 bash

(dentro do container)
#composer install

acesse: localhost:80