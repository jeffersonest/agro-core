# Agro-Core

## Descrição

Este projeto consiste em três repositórios: `agro-front` (frontend) e `agro-backend` (backend) integrados e executados em containers Docker dentro do diretório `agro-core`.
Em cumprimento do desafio: `https://github.com/brain-ag/trabalhe-conosco`. Obs: Necessário ter o [Docker]([https://github.com/jeffersonest/agro-core](https://docs.docker.com/engine/install/)) instalado


## Passos para Executar o Projeto

### 1. Clonar os Repositórios

Clone os repositórios frontend e backend dentro do diretório `agro-core`:

```sh
git clone https://github.com/jeffersonest/agro-front.git frontend
git clone https://github.com/jeffersonest/agro-challenge.git backend
```

### 2. Para executar

Entre no diretório `agro-core` e use o comando:

```sh
docker-compose up --build
```

### 3. Para Acessar

 `Frontend` Disponível em: http://localhost:3000
 
 `Backend` Disponível em: http://localhost:4000/api
 
 `Swagger` Disponível em: http://localhost:4000/api-docs

