# API - Backend Social Network
## Repositório da API do projeto Backend Social Network com recursos de uma rede social.

:green_book: [Documentação para a API](https://documenter.getpostman.com/view/22376211/2s935oLjBq)

:satellite: [Link deploy Render](https://labenu-labook-39.onrender.com)

### Como usar
- Clone o repositório
- Rode `npm i` (ou equivalente) para instalar as dependências
- Crie um arquivo .env na raiz do projeto e preencha os parâmetros:
    - Dados do seu bando de dados
        - DB_HOST=""
        - DB_USER=""
        - DB_PASSWORD=""
        - DB_DATABASE=""
- Rode `npm run migrations` para criar as tabelas no banco de dados (MySQL).
- Teste os endpoints através do arquivo request.rest, Postman ou equivalente.

### Desenvolvimento
- Arquitetura Limpa (Clean Architecture)
- POO (OOP)

### Dependências
* Express
* Cors
* Knex
* MySQL
* Dotenv
* Typescript
* UUID


### Endpoints disponíveis
* Create new user
* Get all users
* Create new post
* Get post info
* Create friendship
* Delete friendship
* Get feed


---
:computer: Desenvolvido por **Rafael Castro**.
