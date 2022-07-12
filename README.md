# kanban-teste

# Começando com Create React App

Este projeto foi inicializado com [Create React App](https://github.com/facebook/create-react-app).

## Scripts Disponíveis

No diretório do projeto, você pode executar:

### Client
#### `npm install` `npm start`

Executa o aplicativo no modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo em seu navegador.

A página será recarregada quando você fizer alterações.\
Você também pode ver erros de lint no console.

### `teste npm`

Inicia o executor de teste no modo de exibição interativa.\
Consulte a seção sobre [execução de testes](https://facebook.github.io/create-react-app/docs/running-tests) para obter mais informações.

### Server
### Clonar o repositório
 - Executar o comando npm i para instalar as dependências
 - Criar o arquivo .env e atualizar as variaveis de ambiente.
  - Exemplo:
   PORT=5000
   MONGODB_URL=mongodb://127.0.0.1:27017/kanban-app
   PASSWORD_SECRET_KEY=esdrasSDASD#81719
   TOKEN_SECRET_KEY=ockas@SSSNCA$1231
 - Executar o comando npm start para rodar o servidor

## Saiba mais

Você pode aprender mais na [documentação Criar aplicativo React](https://facebook.github.io/create-react-app/docs/getting-started).

Para aprender o React, confira a [documentação do React](https://reactjs.org/).

### Divisão de código

Esta seção foi movida para aqui: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code- divisão)

### Analisando o tamanho do pacote

Esta seção foi movida para aqui: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/ docs/analisando-o-tamanho do pacote)

### Fazendo um aplicativo da Web progressivo

Esta seção foi movida para aqui: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react- app/docs/making-a-progressive-web-app)

### Configuração avançada

Esta seção foi movida para aqui: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced- configuração)

### Implantação

Esta seção foi movida para aqui: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` falha ao minificar

Esta seção foi movida para aqui: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/ create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## Instruções

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

## Entrega

 - Para iniciar o teste, crie um repositório no Github, salve o projeto no
repositório e após finalizar, envie-nos o link.
 - Crie um arquivo README explicando o que é preciso para rodar sua
aplicação.
