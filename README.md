<h1 align="center">
    <img alt="Be The Hero" title="logo" src="github/logo.svg" width="100%" />
</h1>

<h2 align="center">
  :rocket: Semana OmniStack 11.0
</h2>

<p align="center">
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#trophy-minhas-implementações">Minhas Implementações</a>
</p>

<p align="center">
  <img alt="By The Hero" src="github/hero.png" width="100%">
</p>

## :computer: Projeto

<strong>Be The Hero</strong> é um projeto da <strong>11º edição da Semana OmniStack.</strong>

O projeto é um sistema de ajuda para ONGs onde uma instituição posta uma caso/<i>incident</i> informando um valor necessário para resolução do problema. A partir daí os <i>Heroes</i> entram em ação contactando a ONG para ajudar coma uma doação financeira.

Na ideia original, a versão Web, feita em React, conta apenas com a parte administrativa para ONGs. Nela uma instituição se cadastra, faz login e cadastra um caso.

Já no aplicativo, desenvolvido em React Native, foi feito apenas a área dos <i>Heroes</i>. Estes visualizam uma lista com os casos de todas as ONGs, acessam os detalhes de um caso e entram em contato, por e-mail ou Whatsapp, diretamente pelo aplicativo.

## :rocket: Tecnologias

### Back-End
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Nodemon](https://www.npmjs.com/package/nodemon)
- [Knex](http://knexjs.org/)
- [SQLite3](https://www.sqlite.org/version3.html)
- [Celebrate](https://www.npmjs.com/package/celebrate)
- [Jest](https://jestjs.io/pt-BR/)
- [Cross-Env](https://www.npmjs.com/package/cross-env)
- [Supertest](https://www.npmjs.com/package/supertest)

### Comandos Back-End
```bash
$ npm init -y (start project)
$ npm install express (framework)
$ node index.js (start application)
$ npm install nodemon -D (Reload application)
$ npm install knex (Query Builder)
$ npm install sqlite3 (Database)
$ npx knex migrate:make create_ongs (create migrations)
$ npx knex migrate:latest (execute migrations)
$ npx knex (list commands knex)
$ npm install celebrate (validation - integrates validation with express)
$ npm install jest (TDD)
$ npx jest --init (Execute init jest)
$ npm install cross-env (Run scripts that set and use environment variables across platforms)
$ npm install supertest (Test Request)
$ npm test (Execute Test)
```


### Front-End
- [React](https://reactjs.org)
- [React Icons](https://www.npmjs.com/package/react-icons)
- [Axios](https://www.npmjs.com/package/axios)
- [React-dom](https://pt-br.reactjs.org/docs/react-dom.html)
- [React-router-dom](https://www.npmjs.com/package/react-router-dom)
- [Intl](https://www.npmjs.com/package/intl)

## Mobile
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)
- [React Icons](https://www.npmjs.com/package/react-icons)
- [Axios](https://www.npmjs.com/package/axios)
- [Intl](https://www.npmjs.com/package/intl)


## :information_source: Como usar ?

### Back-End NodeJS
- Instale as dependencias: npm install
- Execute a aplicação: npm start

### Front-End ReactJS
- Instale as dependencias: npm install
- Execute a aplicação: npm start

### Mobile React Native
- Instale as dependencias: npm install
- Execute a aplicação: npm start


### Comandos Executados -  NodeJS
- npm init -y (start project)
- npm install express (framework)
- node index.js (start application)
- npm install nodemon -D (Reload application)
- npm install knex (Query Builder)
- npm install sqlite3 (Database)
- npx knex migrate:make create_ongs (create migrations)
- npx knex migrate:latest (execute migrations)
- npx knex (list commands knex)
- npm install celebrate (validation - integrates validation with express)
- npm install jest (TDD)
- npx jest --init (Execute init jest)
- npm install cross-env (Run scripts that set and use environment variables across platforms)
- npm install supertest (Test Request)
- npm test (Execute Test)


## Comandos Executados - ReactJS
- npx create-react-app frontend  (start project)
- npm start  (start application)
- cleaning project src(remove -> README.md, App.css, App.test.js, index.css, logo.svg, serviceWorker.js, setupTests.js)
- cleaning project public(remove -> robots.txt, manigest.json, logo512.png, logo192.png)
- npm install react-icons (Icons)
- npm install react-router-dom (Routes)
- npm install axios (Connect backend - Client HTTP)


## Iniciar -  React Native
- Instale as dependencias: npm install
- Execute a aplicação: npm start

## Comandos Executados - React Native
- npm install -g expo-cli  (install expo global)
- expo init mobile (create project)
- Install expo in android/IOS
- yarn start (start application)
- expo install expo-constants (package)
- expo install expo-mail-composer (mail expo)
- yarn add axios (Connect backend - Client HTTP)
- yarn add intl (FormatNumber)
