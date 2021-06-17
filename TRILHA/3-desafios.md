# DESAFIOS Nível 1

## PARTE 1 - Implementar Spring MVC substituido o servlet

O Spring é um dos principais frameworks para Java, com ele o projeto poderá ter um melhor controle de injeção de dependências, além de usá-lo para expor sua API.

Adapte seu projeto do `desafio básico` para o Spring, utilizando o controle de dependência, quando necessário, e substitua a API de servlets por uma implementação utilizando o Spring.

Referências em inglês: https://medium.com/nycdev/java-build-a-tomcat-web-app-with-maven-and-spring-fbc823fa9a37

**Como entrega dessa atividade, envie o link do repositório criado (via LinkedIn ou Email) por avaliação.**

## PARTE 2 - Implementar a persistência usando Hibernate e JPA no Spring

Para diminuir a distância do mundo do banco de dados do mundo orientado a objetos do Java, foi criado o Hibernate e o JPA que abstraem as interações com o banco de dados para uma estrutura orientada a objetos.

Utilizando o Spring, implemente a persistência com os mapeamentos e recursos do Hibernate e do JPA. Ao final deve-se poder realizar operações de CRUD persistindo tudo no banco de dados.

**Como entrega dessa atividade, envie o link do repositório criado (via LinkedIn ou Email) por avaliação.**

## PARTE 3 - Criar integração com a API da Marvel e persistir os dados mais relevantes dos Comics

Geralmente um sistema não vive sozinho, quase sempre temos de implementar integrações com outros sistemas, para buscar ou enviar dados pertinentes ao projeto.

Desenvolva a integração com a API da Marvel, com o serviço /v1/public/comics, usando o RestTemplate para comunicar com a API. De posse dos dados, persista informações relevantes para o projeto, como id, ean, title, description, entre outros.

**Como entrega dessa atividade, envie o link do repositório criado (via LinkedIn ou Email) por avaliação.**

Referências: https://developer.marvel.com/docs

## PARTE 4 - Implementar teste unitários

Teste unitários são de suma importância para que o projeto não apresente muitos bugs e tenha uma vida longa. Eles devem cobrir todas as possibilidades de execução dos métodos, e expor qualquer comportamento inesperado.

Implemente testes unitários em todos os métodos que julgar necessário utilizando o JUnit. Não se esqueça de prever as possibilidades de execução do código.

Garanta pelo menos 75% das linhas do código coberto pelos testes.

**Como entrega dessa atividade, envie o link do repositório criado (via LinkedIn ou Email) por avaliação.**

Referências em inglês: https://en.wikipedia.org/wiki/Code_coverage

## PARTE 5 - Implementar logs utilizando o Log4J

Tanto quanto importante é o funcionamento do sistema são as informações que ele gera de seu funcionamento. Os Logs fornecem para quem for realizar a manutenção do sistema, um detalhamento do que está ocorrendo durante a execução da aplicação, auxiliando a encontrar problemas ou prover auditoria.

Implemente Logs em todo projeto, nos pontos que achar necessário, como por exemplo logs de erros, de inicio e fim de execuções, etc. Para isso implemente a utilização da ferramenta Apache Log4J.

**Como entrega dessa atividade, envie o link do repositório criado (via LinkedIn ou Email) por avaliação.**

Referências em português:

- https://imasters.com.br/back-end/usando-log4j-em-projetos-java
- https://rockcontent.com/br/blog/log-file/
- https://brasil.softlinegroup.com/sobre-a-empresa/blog/armazenamento-de-dados-entenda-a-importancia-para-a-sua-empresa
