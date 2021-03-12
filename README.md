# Ambiente de Postgres e pgAdmin para Banco de Dados 2

## Usando Docker Compose


## Requisitos:

### [Docker](https://docs.docker.com/get-docker/)

### [Docker Compose](https://docs.docker.com/compose/install/)

## Uso do Ambiente

Após a instalação das duas ferramentas, seguir os passos para fazer uso do ambiente:

      git clone https://github.com/TiagoSilva2000/bd2-env.git

      cd bd2-env

      # Crie uma cópia do arquivo .env.example, renomeie essa cópia para .env 
      # e reatribua as variáveis como desejar.

      (sudo) docker-compose up

Para uso de múltiplos usuários simultaneamente, faça uso do pgadmin para se conectar de diferentes formas ao mesmo banco de dados.