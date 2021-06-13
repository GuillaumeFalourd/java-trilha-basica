# Nível 2

## Arquitetura

A arquitetura de um software diz respeito a estrutura e organização do código que o compõe.  Há varios padrões arquiteturais e no backend, o padrão mais comum hoje é o MVC (Model View Controller). Um conceito comum aos vários padrões é a modularização do software. Em Java, o mais comum é modularizar através do Maven.

Nos anexos tem um curso explicando MVC e dois tutoriais de módulos com Maven, um puro Maven e outro com Spring.

Referências em inglês:

- https://www.udemy.com/course/padrao-mvc/
- https://spring.io/guides/gs/multi-module/
- https://maven.apache.org/guides/mini/guide-multiple-modules.html

## SOA

Arquitetura orientada a serviços (SOA) é um tipo de design de software que torna os componentes reutilizáveis usando interfaces de serviços com uma linguagem de comunicação comum em uma rede. ... Esses serviços podem ser acessados remotamente e é possível interagir com eles e atualizá-los de maneira independente.

Referências em português:

- https://www.treinaweb.com.br/blog/voce-sabe-o-que-e-arquitetura-orientada-a-servicos-soa/
- https://www.opus-software.com.br/o-que-e-soa-e-quais-os-beneficios/
- https://www.devmedia.com.br/vantagens-e-desvantagens-de-soa/27437
- https://transformacaodigital.com/tecnologia-da-informacao/desvendando-a-soa-arquitetura-orientada-a-servicos/

## Logs

Log4j é um biblioteca de logs, mas existem outras e elas não seguem a mesma API. Isso faz com que trocar de biblioteca fique díficil. Para simplificar isso, existe o SLF4J, que fornece uma interface padronizada para várias bibliotecas de logs e é muito adotado hoje.

Nos anexos tem um tutorial de SLF4J.

Referências em inglês:

- https://www.tutorialspoint.com/slf4j/index.htm

## Integração

Nem sempre as comunicações funcionam como esperado. Um Back-End não deve contar com um funcionamento perfeito das suas integrações. Ao invés disso, deve ter mecanismos para lidar com as falhas.

Nesse sentido, é comum usar Spring Retry para casos mais simples e o padrão circuit breaker para os mais complexos. Spring Retry foca em configurar retentativas e recuperações para as falhas. Circuit breaker, inspirado em chaves elétricas, permite isso e acrescenta configurações de não realizar a integração quando ela está com muitos problemas.

Nos anexos tem tutorial de cada um dessas tecnologias.

Referências em inglês:

- https://www.baeldung.com/spring-retry
- https://spring.io/guides/gs/circuit-breaker/

## Cacheamento

Em muitos sistemas, existem informações cujo acesso é lento e/ou custoso devido a onde está essa informação. Em alguns casos, é interessante ter a informação disponível em outro lugar de acesso mais fácil e rápido. Essa técnica é conhecida como cache.

No backend, normalmente uma aplicação externa de cache é usado, como o Redis. Para interagir com ele, o Spring disponibiliza o Spring Data Redis, semelhante ao Spring Data usado para persistência.

Nos anexos, há três materiais sobre: a técnica de cache, o Redis sozinho e Spring Data Redis.

Referências em inglês:

- https://www.tutorialspoint.com/redis/index.htm
- https://www.baeldung.com/spring-data-redis-tutorial

Referências em português:

- https://aws.amazon.com/pt/caching/

## NoSQL

Os bancos relacionais, embora muito usados, possuem limitações bastante conhecidas. Quando uma aplicação se depara com uma delas, há outras tecnologias de banco de dados. Elas ficaram conhecidas como NoSQL, hoje abreviação para Not Only SQL.

Um representante muito usado é o Mongo DB, para o qual o Spring possui o Spring Data MongoDB.

No anexo há três materiais sobre: NoSQL em geral, MongoDB sozinho e Spring Data MongoDB.

Referências em inglês:

- https://www.tutorialspoint.com/mongodb/index.htm
- https://spring.io/guides/gs/accessing-data-mongodb/

Referências em português:

- https://aws.amazon.com/pt/nosql/

## Segurança

Segurança é um tema que está cada vez sendo mais discutido no âmbito de software. Num sistema, o Back-End é o mais responsável pela segurança. Normalmente é ele quem define as técnicas e políticas adotadas no projetos.

As duas principais técnicas são autenticação e criptografia. Autenticação envolve a validação da identidade de quem realiza alguma operação. O Spring Security é o módulo do Spring que ajuda nisso. Criptografia trata de ocultar informações sensíveis de forma que só que precise delas tenha acesso. A biblioteca do Java fornece muitos algoritmos de criptografia.

Nos anexos tem um material sobre criptografia, os conceitos e algoritmos, e dois sobre autenticação usando Spring Security.

Referências em inglês:

- https://www.tutorialspoint.com/cryptography/index.htm
- https://spring.io/guides/gs/securing-web/
- https://www.baeldung.com/security-spring

Ferramenta open source: https://horusec.io/site/

## Processamento em lote

Aplicações backend podem precisar realizar processamentos de grande volume de dados e/ou independente das requisições recebidas. Esses são conhecidos por processamentos em lote. O Spring oferece o Spring Batch para construir e configurar esses processamentos e seus agendamentos.

Nos anexos tem dois tutoriais desse biblioteca.

Referências em inglês:

- https://spring.io/guides/gs/batch-processing/
- https://www.tutorialspoint.com/spring_batch/index.htm

## Devops

Devops é um conjunto de práticas e técnicas que visam aproximar o desenvolvedor da parte operacional de um software. Duas muito comuns são expor um API que dá visibilidade sobre o status de execução da aplicação e ter controle sobre o ambiente onde a aplicação executa. Nesse sentido, há, respectivamente,  o framework Spring Boot Actuactor e a tecnologia Docker.

Nos anexos há material explicando a ideia de Devops, o framework e Docker.

Referências em inglês:

- https://www.atlassian.com/devops
- https://spring.io/guides/gs/actuator-service/
- https://spring.io/guides/gs/spring-boot-docker/

Referências em português:

- https://www.fernandoike.com/pt/2020/04/30/devops-e-cultura-ou-ferramentas/
- https://www.devmedia.com.br/curso/curso-docker/2258

## DESAFIO 1: Carrinho do cliente

Para o cliente poder fazer suas compras, é interessante oferecer para ele um carrinho para ir organizando seu potencial pedido.

Implemente um carrinho para os clientes. Um carrinho deve estar associado ao cliente, mas ele só pode ter um. Um carrinho será composto de quadrinhos e a quantidade desejada de cada um.

A API REST de carrinho deve implementar as seguintes operações: adicionar um quadrinho, remover um quadrinho, alterar as quantidades de um quadrinho e listar o carrinho completo.

**Como entrega dessa atividade, me envie o link do repositório criado (LinkedIn ou email).**

## DESAFIO 2: SLF4J e MVC

Uma boa estrutura em uma aplicação é fundamental para entender ela e então poder mantê-la. Dessa boa estrutura fazem parte uma escolha de arquitetura e usar melhor princípios de interfaces vs implementação.

Altere todos os loggers da aplicação para serem do SLF4J ao invés do Log4J. Feito isso, altere a implementação por baixo do SLF4J para Logback ou a biblioteca padrão de logs da JVM.

Organize a sua aplicação segundo os princípios da arquitetura MVC.

**Como entrega dessa atividade, me envie o link do repositório criado (LinkedIn ou email).**
