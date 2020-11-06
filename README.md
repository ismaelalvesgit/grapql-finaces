# Grapql Finances

API GraphQL desenvolvida para afins de projeto piloto em API [GraphQL](https://graphql.org/).

A API foi criada para um Gerenciador de Finanças Pessoais e usa as seguintes tecnologias e recursos:

* NodeJS
* Prisma (Client e Binding)
* GraphQL Yoga
* Moment
* JSON Web Tokens
* Bcrypt
* API GraphQL (Queries e Mutations)
* PM2
* PostgreSQL
* Docker (Compose e Machine)
* Prisma Server

## Screenshots

app view:

<img src="https://raw.githubusercontent.com/ismaelalvesgit/grapql-finaces/master/app.png" width="800">

## Development

### Setup

#### 1) Instalação de dependencias
1º download das dependeicas do projeto
``` sh
npm install
```

#### 2) Iniciar o ambiente backend
``` sh
docker-compose up -d && npm run prisma:deploy 
```

#### 3) Iniciar o servidor de desenvolvimento
```
npm run dev
```

### Build Docker
Para gerar um nova imagem docker do projeto, o arquivo de configuração da imagem está localizado em `Dockerfile`.
``` sh
npm run docker:build
```
Você tambem pode iniciar uma instancia de sua imagem local, o arquivo de configuração da imagem está  localizado em `Dockerfile`.
``` sh
npm run docker:run
```

### Customização de Configurações do projeto
Verifique [Configurações e Referencias](https://www.prisma.io/).

## Contato

Desenvolvido por: [Ismael Alves](https://github.com/ismaelalvesgit)

* Email: [cearaismael1997@gmail.com](mailto:cearaismael1997@gmail.com) 
* Github: [github.com/ismaelalvesgit](https://github.com/ismaelalvesgit)
* Linkedin: [linkedin.com/in/ismael-alves-6945531a0/](https://www.linkedin.com/in/ismael-alves-6945531a0/)