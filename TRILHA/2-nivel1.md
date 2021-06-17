# Nível 1

## Spring

Spring é uma família de frameworks qu#e auxiliam no desenvolvimento de aplicações web na JVM, principalmente Back-End.

Os principais frameworks são:

1) Spring Core - inversão de controle e injeção de dependências
2) Spring Boot - configuração da aplicação
3) Spring MVC - exposição da aplicação via HTTP, muito usado para criação de APIs REST
4) Spring Data - persistência de dados

Nos anexos há tutoriais desses frameworks e de REST.

Referências em inglês:

- https://www.tutorialspoint.com/spring/index.htm
- https://www.tutorialspoint.com/spring_boot/index.htm
- https://spring.io/guides/gs/rest-service/
- https://www.baeldung.com/rest-with-spring-series
- https://www.baeldung.com/persistence-with-spring-series
- https://kotlinlang.org/docs/jvm-spring-boot-restful.html
- https://www.udemy.com/course/spring-framework-5-beginner-to-guru/

Referências em português:

- https://www.devmedia.com.br/exemplo/como-comecar-com-spring/73
- https://www.devmedia.com.br/curso/curso-spring/2316
- https://www.devmedia.com.br/curso/hello-world-com-spring-boot/2327
- https://www.devmedia.com.br/guia/rest-e-java/36819
- https://becode.com.br/o-que-e-api-rest-e-restful/
- https://www.udemy.com/course/restful-apis/
- https://desenvolvimentoparaweb.com/miscelanea/api-restful-melhores-praticas-parte-1/
- https://desenvolvimentoparaweb.com/miscelanea/api-restful-melhores-praticas-parte-2/

## Persistência

O modelo relacional difere do modelo orientado a objetos. Para aproximá-los, existe o mapeamento objeto relacional, ou ORM a sigla em inglês.

Para padronizar persistência de dados em Java, foi criado o padrão JPA, API de persistência Java.

Em Java, Hibernate é o principal ORM e além disso é uma implementação do JPA.

Nos anexos há tutorial de Hibernate e JPA.

Referências em inglês:

- https://www.tutorialspoint.com/jpa/index.htm
- https://www.tutorialspoint.com/hibernate/index.htm
- https://amigoscode.com/p/spring-data-jpa
- https://www.baeldung.com/hibernate-identifiers

Referências em português:

- https://www.devmedia.com.br/guia/hibernate/38312
- https://www.devmedia.com.br/hibernate-validator-validando-dados-no-back-end-com-anotacoes/37979

## Integração

Muitas vezes é necessário interagir com outros sistemas backend, que é conhecido como integração. O Spring oferece o RestTemplate para fazer isso com sistemas REST e a Netflix oferece o Feign. Essas duas soluções são as mais usados hoje.

Nos anexos tem um tutorial de cada.

Referências em inglês:

- https://spring.io/guides/gs/consuming-rest/
- https://www.baeldung.com/intro-to-feign

Referências em português:

- https://eliasjborges.medium.com/consumindo-api-marvel-utilizando-feing-spring-boot-fd945f7614e9

## Testes unitários

A qualidade de código é muito importante em sistemas. Para garantir isso, um padrão é o uso de testes automáticos, mais comumente teste unitários. Em Java, uma unidade é uma classe. Para isolar essa unidade, surge a ideia de mock.

Em Java, as bibliotecas Junit e Mockito são as mais usadas para testes e mocks, respectivamente.

Nos anexos há um curso e um tutorial de Junit e uma serie de tutoriais de Mockito.

Referências em inglês:

- https://www.tutorialspoint.com/junit/index.htm
- https://www.baeldung.com/mockito-series

Referências em português:

- https://www.devmedia.com.br/curso/o-que-e-junit/2075
- https://www.devmedia.com.br/junit-tutorial/1432

## Logs

É necessário saber o que está acontecendo em um Back-End para identificação de problemas. Para isso, é importante registrar alguns detalhes das operações do sistema, usando a tecnologia de logs.

Em Java, Log4J é uma das bibliotecas mais usadas.

No anexo há um tutorial em português e outro em inglês de Log4J.

Referências em inglês:

- https://www.tutorialspoint.com/log4j/index.htm

Referências em português:

- https://www.devmedia.com.br/introducao-ao-log4j/28602
