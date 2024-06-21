<h1 align="center">
  Thoughts
</h1>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=LinkedIn&message=@eudanielcardoso&color=8257E5&labelColor=000000" alt="@eudanielcardoso" />
 <img src="https://img.shields.io/static/v1?label=Tipo&message=API-CRUD&color=8257E5&labelColor=000000" alt="Desafio" />
</p>

Thought Posting System.

O projeto está disponibilizado [nesse github](https://github.com/daniel-alm26/thoughts).

## Tecnologias
 
- [Nodejs](https://nodejs.org/docs/latest-v20.x/api/index.html)
- [Express](https://www.npmjs.com/package/express)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs)
- [connect-flash](https://www.npmjs.com/package/connect-flash)
- [cookie-parser](https://www.npmjs.com/package/cookie-parser)
- [cookie-session](https://www.npmjs.com/package/cookie-session)
- [Express Flash](https://www.npmjs.com/package/express-flash)
- [express-session](https://www.npmjs.com/package/express-session)
- [Sequelize](https://sequelize.org/docs/v6/getting-started/)
- [session-file-store](https://www.npmjs.com/package/session-file-store)
- [express-handlebars](https://www.npmjs.com/package/express-handlebars)

## Práticas adotadas

- MVC

## Como Executar

### Localmente
- Clonar repositório git
```
git clone git@github.com:daniel-alm26/thoughts.git
```
- Instalar os pacotes do projeto o projeto:
```
npm install
```
- Executar:
```
npm start
```
ou
```
yarn start
```

A API poderá ser acessada em [localhost:xxxx](http://localhost:xxxx).

## API Endpoints

Para fazer as requisições HTTP abaixo, foi utilizada a ferramenta [Postman](https://www.postman.com/):

- POST /places
```
http POST :8080/places name="Place" state="State"

HTTP/1.1 200 OK
Content-Length: 129
Content-Type: application/json

{
    "createdAt": "2023-04-20T19:00:07.241632",
    "name": "Place",
    "slug": "place",
    "state": "State",
    "updatedAt": "2023-04-20T19:00:07.241632"
}
```
