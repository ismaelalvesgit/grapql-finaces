# Grapql Finances - @Author Ismael Alves <cearaismael1997@gmail.com>

API GraphQL desenvolvida no curso [Vue JS - Guia Completo (Vue CLI, Vue Router, Vuex e GraphQL)](https://www.udemy.com/course/vue-js-guia-completo/?couponCode=VUE_GITHUB) disponível na Udemy.com.


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

Desenvolvido por: [Plínio Naves](https://www.udemy.com/user/plinio-naves/)

* Email: [cearaismael1997@gmail.com](mailto:cearaismael1997@gmail.com) 
* Github: [github.com/ismaelalvesgit](https://github.com/ismaelalvesgit)
* Linkedin: [linkedin.com/in/ismael-alves-6945531a0/](https://www.linkedin.com/in/ismael-alves-6945531a0/)