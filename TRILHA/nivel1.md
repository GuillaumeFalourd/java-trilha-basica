# Nível 1

## Spring

Spring é uma família de frameworks que auxiliam no desenvolvimento de aplicações web na JVM, principalmente Back-End.

Os principais frameworks são:

1) Spring Core - inversão de controle e injeção de dependências
2) Spring Boot - configuração da aplicação
3) Spring MVC - exposição da aplicação via HTTP, muito usado para criação de APIs REST
4) Spring Data - persistência de dados
5) Spring Cloud - facilita na construção de sistemas em nuvem, além de oferecer vários recursos para o desenvolvimento

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
- https://www.devmedia.com.br/como-criar-sistemas-nas-nuvens-com-spring-cloud/32875

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

Muitas vezes é necessário interagir com outros sistemas backend, que é conhecido como integração. O Spring possui dois tipos de abordagens para fazer integrações REST: O RestTemplate e o OpenFeign. Essas duas soluções são muito utilizadas pelas empresas atualmente.

Nos anexos tem um tutorial de cada.

Referências em inglês:

- https://spring.io/guides/gs/consuming-rest/
- https://www.baeldung.com/spring-cloud-openfeign

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

## DESAFIO 1 - Implementar Spring MVC substituido o servlet

O Spring é um dos principais frameworks para Java, com ele o projeto poderá ter um melhor controle de injeção de dependências, além de usá-lo para expor sua API.

Adapte seu projeto para o Spring, utilizando o controle de dependência, quando necessário, e substitua a API de servlets por uma implementação utilizando o Spring.

Crie uma branch feature/nivel1/desafio1 e coloque o desenvolvimento do desafio nela. Como entrega dessa atividade, adicione o link dessa branch na ISSUE que foi aberta no Desafio 1 do nível Básico.

Referências em inglês:

- https://medium.com/nycdev/java-build-a-tomcat-web-app-with-maven-and-spring-fbc823fa9a37

## DESAFIO 2 - Implementar a persistência usando Hibernate e JPA no Spring

Para diminuir a distância do mundo do banco de dados do mundo orientado a objetos do Java, foi criado o Hibernate e o JPA que abstraem as interações com o banco de dados para uma estrutura orientada a objetos.

Utilizando o Spring, implemente a persistência com os mapeamentos e recursos do Hibernate e do JPA. Ao final deve-se poder realizar operações de CRUD persistindo tudo no banco de dados.

**Como entrega dessa atividade, me envie o link do repositório criado (LinkedIn ou email).**

## DESAFIO 3 - Criar integração com a API da Marvel e persistir os dados mais relevantes dos Comics

Geralmente um sistema não vive sozinho, quase sempre temos de implementar integrações com outros sistemas, para buscar ou enviar dados pertinentes ao projeto.

Desenvolva a integração com a API da Marvel, com o serviço /v1/public/comics, usando o RestTemplate para comunicar com a API. De posse dos dados, persista informações relevantes para o projeto, como id, ean, title, description, entre outros.

**Como entrega dessa atividade, me envie o link do repositório criado (LinkedIn ou email).**

Referências: https://developer.marvel.com/docs

## DESAFIO 4 - Implementar teste unitários

Teste unitários são de suma importância para que o projeto não apresente muitos bugs e tenha uma vida longa. Eles devem cobrir todas as possibilidades de execução dos métodos, e expor qualquer comportamento inesperado.

Implemente testes unitários em todos os métodos que julgar necessário utilizando o JUnit. Não se esqueça de prever as possibilidades de execução do código.

Garanta pelo menos 75% das linhas do código coberto pelos testes.

**Como entrega dessa atividade, me envie o link do repositório criado (LinkedIn ou email).**

Referências em inglês:

- https://en.wikipedia.org/wiki/Code_coverage

## DESAFIO 5 - Implementar logs utilizando o Log4J

Tanto quanto importante é o funcionamento do sistema são as informações que ele gera de seu funcionamento. Os Logs fornecem para quem for realizar a manutenção do sistema, um detalhamento do que está ocorrendo durante a execução da aplicação, auxiliando a encontrar problemas ou prover auditoria.

Implemente Logs em todo projeto, nos pontos que achar necessário, como por exemplo logs de erros, de inicio e fim de execuções, etc. Para isso implemente a utilização da ferramenta Apache Log4J.

**Como entrega dessa atividade, me envie o link do repositório criado (LinkedIn ou email).**

Referências em português:

- https://imasters.com.br/back-end/usando-log4j-em-projetos-java
- https://rockcontent.com/br/blog/log-file/
- https://brasil.softlinegroup.com/sobre-a-empresa/blog/armazenamento-de-dados-entenda-a-importancia-para-a-sua-empresa
