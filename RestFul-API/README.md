# RESTful API de Usuários

Restful-API desenvolvida desenvolvida no Curso Completo de JavaScript na Udemy.com em 2021
(https://www.udemy.com/course/javascript-curso-completo/). 

### Instalação
```
npm install
```

### Excutando servidor
```
npm start
```
## Rotas
Obter todos os usuários:
```
GET /users
```
Exemplo de resultado:
```json
{
    "users":[]
}
```

Cadastrar um novo usuário:
```
POST /users
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Obter dados de um usuário:
```
GET /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324",
    "name":"João Rangel"
}
```

Editar um usuário:
```
PUT /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```

Excluir um usuário:
```
DELETE /users/:id
```
Exemplo de resultado:
```json
{
    "_id":"hjkhfui324"
}
```