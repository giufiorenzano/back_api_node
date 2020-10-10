# back_api_node
 Api em Node.js

 ## Descrição
 Api em Node.js para ser usado no back end de uma aplicação em Angular.

 ### Pré-Requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/edinilsonvida/back_api_node>

# Acesse a pasta do projeto no terminal/cmd
$ cd back_api_node

# Vá para a pasta server
$ cd server

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm start

# O servidor inciará na porta:3000 - acesse <http://localhost:3000>
```
 primeiro passo: npm install no servidor
 segundo passo: nodemon server.js
 terceiro passo: criar schema no mysql
 quarto passo: alterar nome(db) e senha no db.config
 quinto passo: testar as rotas
-POST http://localhost:3000/api/posts
-GET http://localhost:3000/api/posts
-GET http://localhost:3000/api/posts/:id
-PUT http://localhost:3000/api/posts/:id
-GET http://localhost:3000/api/posts?title=[?]
-GET http://localhost:3000/api/posts/published
-DELETE http://localhost:3000/api/posts/:id
-DELETE http://localhost:3000/api/posts/
