# API REST - ToDo Sample

Ejemplo simple de API REST usando

    π― "cors": "^2.8.5"
    π― "dotenv": "^16.0.1"
    π― "express": "^4.18.1"
    π― "express-validator": "^6.14.1"
    π― "mongoose": "^6.3.6"
    π― "morgan": "^1.10.0"


<!-- 
# v1

[![En Heroku](<img src="https://www.svgrepo.com/show/331424/heroku.svg" alt="drawing" width="50"/>)](https://api-rest-todo-sample.herokuapp.com/api/v1)


<img src="https://www.svgrepo.com/show/331424/heroku.svg" alt="drawing" width="50"/>


Utiliza MongoDB como motor de base de datos 
[https://api-rest-todo-sample.herokuapp.com/api/v1](https://api-rest-todo-sample.herokuapp.com/api/v1)

- se ocupan la variable de entorno **MONGO_URI** para conectarse a la base de datos -->


## β¨ CaracterΓ­sticas:
- β *Deploy* en Heroku.
- βCrear pagina de inicio y 404
- β Crear la v1 - usando [MongoDB/MongoAtlas](https://api-rest-todo-sample.herokuapp.com/api/v1)
- β Crear la V2 - usando [Postgres](https://api-rest-todo-sample.herokuapp.com/api/v2)
- β Crear la V3 - usando MySQL


## π Estructura del proyecto
```
/
βββ βpublic/
β   βββ index.html
β   βββ favicon.ico
βββ src/
β   βββ index.js
β   βββ app.js
β   βββ controllers/
β   β   βββ task.v1.controllers.js
β   βββ databases/
β   β   βββ databases.js
β   βββ routes/
β   β   βββ task.v1.routes.js
β   βββ models/
β   β   βββ task.v1.models.js
β   βββ utils/
β       βββ task.v1.validations.js
βββ package.json
```

| Commandos         | AcciΓ³n                                                           |
|:----------------  |:---------------------------------------------------------------- |
| `npm install`     | Instala las dependencias necesarias del proyecto                 |
| `npm run dev`     | Inicia el servidor local como desallorrador en `localhost:3000`  |
