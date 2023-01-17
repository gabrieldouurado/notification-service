# Notification Service
O software desenvolvido é um serviço de notificação que integrará um projeto com a arquiterura de microsserviços.

Ele foi construido utilizando o framework *Nest.Js* devido as facilidades de utlizar práticas como Injeção de Dependências e Inversão de Dependência.

Dentro do projeto foram utilizado vários Design Patterns:
- In Memory Database
- Value Objects
- Repository Pattern
- Data Transfer Objects
- Mappers
- Factory

Além de abordar práticas de DDD, como inversão e injeção de dependencias, entidades, separação da camada de domínio, desacoplamento dentre outras

O ORM escolhido para o projeto foi o Prisma, ele já possui integração documentada com o framework e com typescript. O banco de dados escolhido foi o SQLite para reduzir a complexidade do projeto, esse banco de dados pode ser facilmente substituido, o prisma fornece integração com diversos outros banco de dados.

## Executando o Projeto
Antes de executar o projeto é necessário instalar as dependências:

```
npm install
```

Para iniciar o projeto em modo de desenvolvimento:

```
npm run start:dev
```

## Consumindo o Projeto
É possível consumir o projeto usando RESTApi, para faciliar o seu uso, na pasta ``/docs`` tem uma collection do Postman com todas as rodas disponíveis no projeto.

## Executando os Testes
Está sendo utilizada a biblioteca ``jest`` executar os testes unirários do projeto. 
Para inicar os testes:

```
npm test
```