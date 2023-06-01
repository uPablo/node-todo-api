# node-todo-api

Projeto feito no módulo do curso Node + Typescript

### Descrição
Criação de uma api simples utilizando o príncipio REST.
Rotas

`[GET] /todo` - Para listagem de todas tarefas

`[POST] /todo` - Para criação de uma tarefa

`[PUT] /todo/:id` - Para atualizar uma tarefa utilizando um ID válido

`[DELETE] /todo/:id` - Para exclusão de uma tarefa utilizando um ID válido

### Screenshot da aplicação no Postman e seus respectivos retornos
`[GET]`
![nodejs-todo-api-get](https://raw.githubusercontent.com/uPablo/node-todo-api/main/assets/nodejs-todo-api-get.png)

`[POST]`
![nodejs-todo-api-post](https://raw.githubusercontent.com/uPablo/node-todo-api/main/assets/nodejs-todo-api-post.png)

`[PUT]`
![nodejs-todo-api-put](https://raw.githubusercontent.com/uPablo/node-todo-api/main/assets/nodejs-todo-api-put.png)

`[DELETE]`
![nodejs-todo-api-delete](https://raw.githubusercontent.com/uPablo/node-todo-api/main/assets/nodejs-todo-api-delete.png)

### Renomear o arquivo `.env.example` para `.env` e configurar porta e banco de dados
```
PORT=4000

PG_DB=note_todo_simples
PG_USER=postgres
PG_PASSWORD=
PG_PORT=5432
```

### Importar o arquivo 
`sources/API Node - To-do Simples.postman_collection.json` no `Postman`

### Importar o banco de dados 
`sources/note_todo_simples.sql` no banco de dados `postgres`

### Instalação
`npm install`

### Para rodar o projeto
`npm run start-dev`
