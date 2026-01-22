## REST Client

Projeto backend desenvolvido em Java com o objetivo de expor e consumir uma API REST, aplicando conceitos fundamentais de arquitetura em camadas, tratamento de exceções e organização de código.

O foco do projeto é entender o fluxo completo de uma API, desde a requisição HTTP até a persistência e retorno dos dados.

## 🎯 Objetivo do projeto

Praticar o desenvolvimento de APIs REST em Java

Aplicar separação de responsabilidades em camadas

Trabalhar com DTOs para controle de dados

Implementar tratamento de exceções padronizado

Consolidar fundamentos de backend

## 🗂️ Estrutura do projeto

```
src/main/java/com/caiowilker/rest_client
├── controller
│   └── ClientController.java        # Camada responsável pelas requisições HTTP
├── service
│   └── ClientService.java           # Regras de negócio da aplicação
├── repository
│   └── ClientRepository.java        # Comunicação com a base de dados
├── entities
│   └── Client.java                  # Entidade principal do domínio
├── DTO
│   └── ClientDTO.java               # Objeto de transferência de dados
├── handler
│   ├── ResourceExceptionHandler.java # Tratamento global de exceções
│   ├── ResourceNotFoundException.java
│   ├── DatabaseException.java
│   └── StandardError.java            # Modelo padrão de erro
└── RestClientApplication.java        # Classe principal da aplicação

```

⚠️ Observação: a organização segue o padrão mais comum em aplicações backend Java, facilitando manutenção e escalabilidade.

## 🛠️ Tecnologias utilizadas

Java

Spring Boot

API REST

Maven

JPA / Repository Pattern

Tratamento de exceções HTTP

## ⚙️ Funcionalidades

Cadastro de clientes via API REST

Consulta de dados utilizando endpoints HTTP

Uso de DTO para controle da exposição de dados

Tratamento padronizado de erros e exceções

Separação clara entre controller, service e repository

## ▶️ Como executar o projeto

Clonar o repositório

Abrir o projeto em uma IDE (IntelliJ, Eclipse ou VS Code)

Executar a classe RestClientApplication

Testar os endpoints utilizando Postman, Insomnia ou navegador

## 📚 Aprendizados

Organização de aplicações backend em camadas

Importância do DTO para segurança e clareza da API

Tratamento correto de exceções em APIs REST

Fluxo completo de uma requisição HTTP no backend

## 🚀 Observação final

Este projeto faz parte do meu processo de formação como estudante de Engenharia da Computação, com foco em backend, boas práticas e entendimento real da arquitetura, indo além de exemplos simples de curso.


