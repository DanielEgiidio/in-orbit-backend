<h1 align="center">
  In.Orbit
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/danielegiidio/in-orbit-backend">

  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/danielegiidio/in-orbit-backend" />

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/danielegiidio/in-orbit-backend">
  
  <a href="https://github.com/danielegiidio/in-orbit-backend/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/danielegiidio/in-orbit-backend">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-blue">


</p>

<p align="center" >
  <img src="https://i.ibb.co/ygYnbcr/Cover-1.png" alt="Capa do projeto"  />
</p>



## 💻 About

Aplicação back-end desenvolvida em Node.js e TypeScript, que implementa uma API REST. O projeto utiliza o framework Fastify para a construção da API, e o DrizzleORM para a integração com o banco de dados PostgreSQL. Ele também emprega Docker para containerização e Zod para validação de dados. A aplicação serve como um gerenciador de metas, permitindo a criação e acompanhamento de metas, bem como o monitoramento de suas conclusões semanais.


## 💡Description

- Gerenciamento de Metas: Criação, acompanhamento e finalização de metas.
- Acompanhamento Semanal: Consulta de metas pendentes baseadas em frequência semanal.
- Validação de Dados: Validação de entradas da API utilizando Zod.




### 📝 Requisites

Antes de baixar o projeto você vai precisar ter instalado na sua máquina as seguintes ferramentas:

* [Git](https://git-scm.com)
* [NodeJS](https://nodejs.org/en/)
* [Docker](https://hub.docker.com/r/bitnami/postgresql)
* [NPM](https://www.npmjs.com/)

Para testar as rotas da aplicação você pode usar o cliente HTTP [Postman](https://www.postman.com/)

### ⚙ Setup

Passo a passo para clonar e executar a aplicação na sua máquina:

```bash
# Clone este repositório
$ git clone https://github.com/DanielEgiidio/in-orbit-backend.git

# Instale as dependências
$ npm install

# Crie o arquivo '.env' e preencha as variáveis conforme o arquivo '.env.example' 

# Execute as migrations para criar as tabelas necessários no banco
$ npx drizzle migrate

# Mantenha o seu container do docker local ativo
$ docker compose up -d

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# A aplicação inciará na porta que você configurou no arquivo '.env' 
```


## 🛠 Technologies

As seguintes principais ferramentas foram usadas na construção do projeto:

- **[TypeScript](https://www.typescriptlang.org/)**
- **[Node](https://nodejs.org/pt)**
- **[Fastify](https://fastify.dev/)**
- **[DrizzleORM](https://orm.drizzle.team/)**
- **[Zod](https://zod.dev/)**
- **[Docker](https://hub.docker.com/r/bitnami/postgresql)**
- **[PostegreSQL](https://www.postgresql.org/)**
- **[DayJS](https://day.js.org/)**

> Para mais detalhes das dependências gerais da aplicação veja o arquivo [package.json](./package.json)


## 📝 License

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para mais informações

