# SOA - Microservices and Web Engineering

## CheckPoint 1 | 1º semestre | 2025 - 3 SIR

# CRUD para Gerenciamento de Pacientes

## Desenvolvido por:

- **Paulo Henrique** | RM 552444
- **Pedro Cavariani** | RM 551380

## Descrição do Projeto

Este projeto tem como objetivo a criação de uma **API RESTful** para o gerenciamento de uma agenda de pacientes. A API permite realizar operações de **CRUD** (Criar, Ler, Atualizar e Excluir) para a entidade **Paciente**, utilizando o ID como identificador.

## Funcionalidades e Métodos

- **Criar um paciente** → `POST /pacientes`
- **Deletar um paciente** → `DELETE /pacientes/{id}`
- **Atualizar um paciente** → `PUT /pacientes/{id}`
- **Buscar todos os pacientes** → `GET /pacientes`
- **Buscar paciente por ID** → `GET /pacientes/{id}`

## Tecnologias Utilizadas

- **Spring Boot** → Desenvolvimento da API
- **Java 17** → Linguagem de programação
- **Swagger OpenAPI** → Documentação interativa da API
- **Maven** → Gerenciamento de dependências e build

## Requisitos para Execução

Antes de rodar a aplicação, certifique-se de:

1. Ter o **JDK 17** (ou superior) e o **Maven** instalados.
2. Configurar o **Swagger** corretamente.

### Configuração do Swagger

No arquivo `application.properties`, adicione as seguintes configurações:

```properties
springdoc.swagger-ui.path=/ 
springdoc.swagger-ui.disable-swagger-default-url=true
```
Mais informações: [SpringDoc OpenAPI](https://springdoc.org/properties.html)

## Executando a Aplicação

Para iniciar a API, utilize o seguinte comando no terminal:
```sh
mvn spring-boot:run
```

## Acessando a Documentação da API

Após a execução, a documentação interativa do Swagger estará disponível em: [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)
