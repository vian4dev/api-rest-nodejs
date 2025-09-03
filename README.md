<div align="center">
  <a href="https://github.com/vian4dev/api-rest-nodejs/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/vian4dev/api-rest-nodejs?style=social">
  </a>
  
  <img alt="PRs welcome!" src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=7159c1&labelColor=000000" />
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=7159c1&labelColor=000000">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vian4dev/api-rest-nodejs?color=%2304D361">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/vian4dev/api-rest-nodejs">
	
  <a href="https://github.com/vian4dev/api-rest-nodejs/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vian4dev/api-rest-nodejs">
  </a>
  
  <a href="https://www.linkedin.com/in/vianadev/">
    <img alt="Made by vian4dev" src="https://img.shields.io/badge/made%20by-vian4dev-%2304D361">
  </a>
</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/vian4dev/vian4dev/bfae0da7d97ab8f10a008d3fdea6f2e2181fa3ca/.github/rocketseat.svg" width="250" height="250" alt="Rocketseat">
</div>

# API NODE REST

## ✒️ Descrição
Essa e uma API REST desenvolvida em NodeJS que lista transações financeiras, utilizando  Fastify, Knex, TypeScript entre outras ferramentas. 

## 🚀 Tecnologias utilizadas
<div style="display: inline_block"><br>
  <img align="center" alt="img-nodejs" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/54cfe13ac10eaa1ef817a343ab0a9437eb3c2e08/icons/nodejs/nodejs-plain-wordmark.svg">
	
  <img align="center" alt="img-typescript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg">

  <img align="center" alt="img-fastify" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/54cfe13ac10eaa1ef817a343ab0a9437eb3c2e08/icons/fastify/fastify-original.svg">

  <img align="center" alt="img-knex" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/54cfe13ac10eaa1ef817a343ab0a9437eb3c2e08/icons/knexjs/knexjs-original.svg">
</div>

## ✅ Requisitos da Aplicação

### RF
- [x] O usuário deve poder criar uma nova transação;
- [x] O usuário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;
### RN
- [x] A transação pode ser do tipo crédito que somará ao valor total, ou débito subtrairá;
- [x] Deve ser possível identificarmos o usuário entre as requisições;
- [x] O usuário só pode visualizar transações o qual ele criou;

## 📷 Demostração

## 🔥 Instalação
Clone o repositório.
~~~
git clone https://github.com/vian4dev/api-rest-nodejs.git
~~~
Acesse o diretório do projeto.
~~~
cd api-rest-nodejs/
~~~
Instale as dependências.
~~~
npm install 
~~~
Crie o arquivo .env na raiz do diretório.
~~~
NODE_ENV=development
DATABASE_CLIENT=sqlite
DATABASE_URL=./db/app.db"
~~~
Execute a migrations.
~~~
npm run knex -- migrate:latest
~~~
Execute a aplicação.
~~~
npm run dev
~~~

## 📝 Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
<div align="center"> 
 <p>Desenvolvido por - <a href="https://github.com/vian4dev">Gabriel Viana</a> 🤖</p>
 
 <a href="https://www.linkedin.com/in/vianadev" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>


