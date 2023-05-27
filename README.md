<h1 align="center">
    <img alt="Memories" src=".github/nlw-spacetime-logo.svg" height="100px" />
    <br>Next Level Week #12<br/>
    Node.js | ReactJS | React Native
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/guipaluri/memories?style=flat-square">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/guipaluri/memories?style=flat-square">
  <img alt="GitHub" src="https://img.shields.io/github/license/guipaluri/memories?style=flat-square"> 
  <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1?style=flat-square"><br/>
</p>
<p align="center">
  <a href="#bookmark-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :bookmark: Sobre

O **Memories** é uma aplicação Web e Mobile construída para servir de "cápsula do tempo", onde o usuário pode cadastrar momentos da vida dele anexando imagens e frases.
  
Essa aplicação foi realizada durante a **Next Level Week #12**, projeto da [Rocketseat](https://rocketseat.com.br/).

## :rocket: Tecnologias

-  [Typescript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [ReactJS](https://reactjs.org/)
-  [React Native](http://facebook.github.io/react-native/)
-  [Expo](https://expo.io/)
-  [Fastify](https://www.fastify.io/)
-  [axios](https://github.com/axios/axios)

## :boom: Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador
  - Também, é **preciso** ter um gerenciador de pacotes seja o **[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**.
  - Por fim, é **essencial** ter o **[Expo](https://expo.io/)** instalado de forma global na máquina

1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/guipaluri/memories.git
```

2. Executando a Aplicação:

```sh
  # API
  $ cd server
  # Instalando as dependências do projeto.
  $ npm install # ou yarn
  # Configurando o banco de dados e criando as tabelas.
  $ npx prisma migrate dev # ou yarn prisma migrate dev

  # Inicie a API
  $ npm run dev # ou yarn dev

  # Aplicação web
  $ cd web
  # Instalando as dependências do projeto.
  $ npm install # ou yarn
  # Inicie a aplicação web
  $ npm run dev # ou yarn start

  # Aplicação mobile
  $ cd mobile
  # Instalando as dependências do projeto.
  $ npm install # ou yarn
  # Inicie a aplicação mobile
  $ npm start # ou yarn start
```


## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---
<sup>Projeto desenvolvido com a tutoria de [Diego Fernandes](https://github.com/diego3g), da [Rocketseat](rocketseat.com.br).</sup>