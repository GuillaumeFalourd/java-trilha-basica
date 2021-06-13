# java-backend-trail

Esse repositório disponibiliza uma versão zero de uma API de cadastro de usuários (Users) ha ser melhorada.

## Como usar?

Na pasta [Trilha Java Back-End](https://github.com/GuillaumeFalourd/java-backend-trail/tree/main/PT) deste repositório, você encontrará varias orientações de estudos da linguagem JAVA com desafios exponenciais para desenvolver de uma API do zero.

## Endpoint disponíveis na versão zero deste repositório

### Criar User

**POST:** `http://localhost:8080/users` com body:

```json
{
    "name":"Name",
    "cpf":"cpf",
    "email":"email",
    "birthDate":"1900-01-01"
}
```

### Obter User com CPF

**GET:** `http://localhost:8080/users/{cpf}` vai returnar:

```json
{
    "name":"Name",
    "cpf":"cpf",
    "email":"email",
    "birthDate":"1900-01-01",
    "vehicles": ["..."]
}
```

## Referências legais no Github

Alguns repositórios do Github são muito legais para aprender mais a respeito de Java. 
Seguem alguns deles:

- [Spring-Boot](https://github.com/spring-projects/spring-boot)
- [Java Design Patterns](https://github.com/iluwatar/java-design-patterns)