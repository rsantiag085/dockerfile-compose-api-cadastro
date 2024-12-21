# dockerfile-compose-api-cadastro

## Descrição
Este projeto contém uma API de cadastro desenvolvida com Node.js e Express. A API permite gerenciar usuários, com endpoints para consultar os dados. O ambiente foi configurado utilizando Docker e Docker Compose para facilitar a execução e o deploy da aplicação. 

A API é ideal para aprender a configurar e rodar aplicações Node.js em containers Docker.

Link do projeto original - https://github.com/fraigo/node-express-rest-api-example

---

## Passos para Build e Execução

### Pré-requisitos:
1. Certifique-se de que o [Docker](https://www.docker.com) e o [Docker Compose](https://docs.docker.com/compose/) estão instalados em sua máquina.

### Instruções:
1. Clone este repositório:
   git clone https://github.com/seu-usuario/dockerfile-compose-api-cadastro.git
   cd dockerfile-compose-api-cadastro

2. Construa e inicie o container com o Docker Compose:
   docker-compose up --build

3. O Docker Compose irá:
   - Construir a imagem Docker a partir do `Dockerfile`.
   - Iniciar o container da API mapeando a porta `8080`.

---

## Como Acessar a API
Após rodar o comando acima, você pode acessar a API localmente no navegador ou no Postman:

### URL da API:
http://localhost:8080


### Exemplos de Endpoints:
1. **GET /api/users**  
   Retorna a lista de usuários cadastrados.

   Exemplo no terminal usando `curl`:
   curl http://localhost:8080/api/users

2. **POST /api/users**  
   (Se implementado no projeto) Permite adicionar um novo usuário. Envie os dados no corpo da requisição em formato JSON.

---

## Estrutura do Projeto
- **Dockerfile:** Configura a imagem da API Node.js.
- **docker-compose.yml:** Define como os containers serão configurados e conectados.
- **README.md:** Instruções para executar o projeto.

---

## Link do Repositório
[https://github.com/seu-usuario/dockerfile-compose-api-cadastro](https://github.com/seu-usuario/dockerfile-compose-api-cadastro)

