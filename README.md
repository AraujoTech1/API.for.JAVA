<h1 align="center"> API REST com Java e Spring Boot </h1>


## Descrição do Projeto

Este projeto consiste em uma **API RESTful** desenvolvida utilizando **Java 23** e **Spring Boot**. O objetivo principal é oferecer uma estrutura simples e eficiente para a criação de APIs, com foco em performance e escalabilidade.

A aplicação foi construída para demonstrar a criação de endpoints, manipulação de dados e utilização de recursos como persistência e testes automatizados. O projeto é totalmente configurado com **Maven**, o que facilita o gerenciamento de dependências e a construção da aplicação.


## Funcionalidades do Projeto

- **Endpoints RESTful**: O projeto oferece endpoints para realizar operações básicas de CRUD (Create, Read, Update, Delete).
- **Persistência de Dados**: Utiliza o **Spring Data JPA** para persistir dados em um banco de dados relacional (MySQL, PostgreSQL, ou outro de sua escolha).
- **Testes Automatizados**: A aplicação conta com testes de unidade e integração, garantindo que todas as funcionalidades estejam funcionando corretamente.
- **Documentação Automática**: A API conta com documentação gerada automaticamente através do **Swagger**.
 

## Testes de Software

### 📌 Testes de Depuração
- A aplicação inclui testes unitários básicos com **JUnit** para garantir que cada método do serviço esteja funcionando corretamente.

### 📌 Testes de Funcionamento
- **Testes de API**: Testes de integração foram implementados utilizando o **Spring Boot Test**, garantindo que os endpoints estejam respondendo corretamente e conforme o esperado.
- **Testes com Postman**: Endpoints foram testados manualmente com o Postman para garantir sua funcionalidade e validar a comunicação com o backend.

### 📌 Imagem do Teste

- Captura do teste realizado:

![Imagem teste](https://github.com/AraujoTech1/API.for.JAVA/blob/master/img/Captura%20de%20tela%202025-03-11%20145528.png)


## Tecnologias Utilizadas

![Java](https://img.shields.io/badge/Java-23-orange?logoWidth=40)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-v2.5-blue?logoWidth=40)
![Maven](https://img.shields.io/badge/Maven-3.8.1-green?logoWidth=40)
![GitHub](https://img.shields.io/badge/GitHub-API--for--JAVA-purple?logoWidth=40)
![VS Code](https://img.shields.io/badge/VS%20Code-1.79-blue?logo=visualstudiocode&logoWidth=40)
![Git](https://img.shields.io/badge/Git-2.39.1-orange?logo=git&logoWidth=40)


## Bibliotecas e Frameworks

- **Spring Boot**: Framework para criação de aplicações Java baseadas no Spring.
- **Spring Data JPA**: Biblioteca para persistência de dados com banco de dados relacional.
- **JUnit**: Framework para testes unitários.
- **Swagger**: Para documentação automática da API.
- **Postman**: Utilizado para testar manualmente os endpoints.
  

## Instruções para Execução

1. Clonar o repositório
2. Instalar Dependências com Maven:

- No terminal, execute o seguinte comando para instalar as dependências:

 ```mvn install```

3. Executar a Aplicação:

- Para iniciar uma API, execute o comando:

```mvn spring-boot:run```

4. Acessar a API:

- A API estará disponível no endereço:

```http://localhost:8080``` 


---
<p align="right">
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" height="30" alt="windows8 logo" />
</p>


