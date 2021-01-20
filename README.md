<h3 align="center">
	BootCamp Gostack - Desafio 6 - Database-upload
</h3>
<p align="center">
  Um desafio bem parecido com o anterior onde se deveria completar o código de uma API que cria transações de entras e saídas, dessa vez utilando banco de dados e upload de arquivos.
</p>

<p align="center">
  <a href="#gear-como-rodar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-tecnologias-usadas-neste-projeto">Tecnologias</a>
</p>

</br>

<div align="center">
  <a href="https://insomnia.rest/run/?label=Desafio%20Database-upload&uri=https%3A%2F%2Fgithub.com%2FAlexBitar80%2FDatabase-upload%2Fblob%2Fmaster%2FInsomnia_2020-11-25.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</div>

## :computer: Tecnologias usadas neste projeto

O projeto está utilizando as seguintes tecnologias:

-  [TypesScript](https://www.typescriptlang.org/)
-  [Node.js](https://nodejs.org/en/)
-  [Jest](https://jestjs.io/)
-  [PostgreSQL](https://www.postgresql.org/)
-  [TypeORM](https://typeorm.io/#/)
-  [Multer](https://www.npmjs.com/package/multer)
-  [Express](https://expressjs.com/pt-br/)
-  [ts-node-dev](https://www.npmjs.com/package/ts-node-dev)

## :gear: Como rodar

Para clonar e rodar esse projeto você vai precisar do [Node](https://nodejs.org/en/) do [Npm](https://www.npmjs.com/get-npm) ou do [Yarn](https://yarnpkg.com/) e do [Git](https://git-scm.com/) instalado na rua máquina.
Para criar a instancia do banco de dados eu estou usando o [Docker](https://docs.docker.com/get-docker/), instale-o e inicie uma instancia antes de rodar as migrations

```bash
# Faça o clone deste repositório para qualquer pasta de sua preferencia
$ git clone https://github.com/AlexBitar80/Database-upload

# Vá até essa pasta
$ cd Database-upload-master

# rode esses comandos para instalar as dependências
$ yarn || npm install

# rode esses comandos para rodar as migrations
$ yarn typeorm migration:run || npm run typeorm migration:run

# use esses comandos para rodar a API
$ yarn dev:server || npm run dev:server

# use esses comandos para rodar os testes
$ yarn test || npm run test

```
