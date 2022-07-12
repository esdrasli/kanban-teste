# Desafio Kanban
## Instruções do desafio

Você deve desenvolver uma API, utilizando Node.JS, e um projeto frontend,
utilizando ReactJs para uma aplicação de quadro Kanban.
A escolha das bibliotecas, arquitetura, etc, fica a seu critério, porém deverá ser
utilizado como banco de dados o MongoDB

## API

A API precisa ser desenvolvida em Node.JS, e deverá ser possível: - Listar todas as
tarefas. - Adicionar uma nova tarefa. - Alterar uma tarefa. - Deletar uma tarefa.

## FRONTEND

O frontend precisa ser construído com ReactJs, e deverá ser possível:
 - Listar as tarefas separadas por status(pending, in progress, testing, done)
 - Componente para adicionar nova tarefa
 - Editar tarefa
 - Mudar o status de uma tarefa
 - Deletar tarefa

# Começando com Create React App

Este projeto foi inicializado com [Create React App](https://github.com/facebook/create-react-app).

## Scripts Disponíveis

### Clonar o repositório

### Client
No diretório do projeto, você pode executar:

#### `npm install` `npm start`

Executa o aplicativo no modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo em seu navegador.

A página será recarregada quando você fizer alterações.\
Você também pode ver erros de lint no console.

### Server
 - Executar o comando `npm i` para instalar as dependências
 - Criar o arquivo .env e atualizar as variaveis de ambiente.
  - Exemplo:\
   PORT=5000\
   MONGODB_URL=mongodb://127.0.0.1:27017/kanban-app \
   PASSWORD_SECRET_KEY=esdrasSDASD#81719 \
   TOKEN_SECRET_KEY=ockas@SSSNCA$1231 \
 - Executar o comando `npm start` para rodar o servidor

## Saiba mais

Você pode aprender mais na [documentação Criar aplicativo React](https://facebook.github.io/create-react-app/docs/getting-started).

Para aprender o React, confira a [documentação do React](https://reactjs.org/).
