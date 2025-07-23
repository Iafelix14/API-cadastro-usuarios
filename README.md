# API de Cadastro de Usuários


## 🎯 Objetivo do Projeto

  Este projeto tem como objetivo demonstrar a construção de uma API RESTful completa utilizando **Java 21** com **Spring Boot**, seguindo os princípios de **Clean Code**, **boas práticas de arquitetura** e organização de código.
  A aplicação realiza um CRUD (Create, Read, Update, Delete) de usuários, persistindo os dados em um banco de dados **H2** (em memória),  com foco em um CRUD completo para gerenciamento de usuários, ideal para testes e desenvolvimento local.

  O projeto foi pensado de forma didática, com explicações claras e estrutura limpa, para que desenvolvedores iniciantes ou em transição de carreira possam entender passo a passo como funciona a criação de uma API moderna com Java. Toda a estrutura foi separada por camadas (Controller, Service, Repository e Model), com documentação dos endpoints e versionamento no GitHub.

  Ideal para quem está começando no backend e quer uma base sólida para projetos futuros!🚀



---



## 🚀Stacks Utilizadas



- Java 21  

- Spring Boot 3.x  

- Spring Data JPA  

- Banco de dados H2 (em memória)  

- Postman (para testes da API)  

- Git/GitHub (versionamento)



---



## 🧠 O que é um CRUD?



**CRUD** é o acrônimo de:



- **C**reate — Criar um novo usuário  

- **R**ead — Ler/listar usuários  

- **U**pdate — Atualizar dados de um usuário  

- **D**elete — Deletar usuário da base  



Essa API entrega essas 4 operações de forma simples e organizada, com boas práticas de clean code.



---



## 📂 Estrutura do Projeto



```bash

src/

├── main/

│   ├── java/

│   │   └── com/iafelix14/apicadastro/

│   │       ├── controller/

│   │       │   └── UserController.java

│   │       ├── model/

│   │       │   └── User.java

│   │       ├── repository/

│   │       │   └── UserRepository.java

│   │       └── service/

│   │           └── UserService.java

│   └── resources/

│       └── application.properties

├── test/

│   └── java/

│       └── ... (testes da API)
└── pom.xml


## Endpoints da API

```http
POST /users → Criar um novo usuário
GET /users → Listar todos os usuários
GET /users/{id} → Buscar usuário por ID
PUT /users/{id} → Atualizar usuário por ID
DELETE /users/{id} → Deletar usuário por ID

