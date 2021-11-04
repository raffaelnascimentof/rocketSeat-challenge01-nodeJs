# rockertSeat-challenge01-nodeJs

Desafio um do Ignite Rocketseat trilha de NodeJS.

Sisteminha para gerenciar tarefas.

# Como rodar ?

Clonar projeto para o computador e rodar yarn install para baixar todas as dependências do projeto.

Comando: yarn dev para subir o projeto.

Comando: yarn test para rodar os testes do projeto.

# Endpoints

Todos em localhost:3333.

POST -> /users <br>
```
Body:
{
	"name": "nome",
	"username": "username"
}
```
POST - /todos
```
Body:
{
	"title": "titulo",
	"deadline": "2021-11-25"
}

Header:
username: username
```

GET - /todos
```
Header:
username: username
```

PUT - /todos/:id
```
Body:
{
	"title": "titulo",
	"deadline": "2021-11-25"
}

Header:
username: username
```

PATCH - /todos/:id/done
```
Header:
username: username
```

DELETE - /todos/:id
```
Header:
username: username
```
