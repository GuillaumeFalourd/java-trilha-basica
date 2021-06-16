# Nível Básico

## Primeiros passos em JAVA

Java é uma linguagem de programação orientada a objetos de propósito geral, concorrente, fortemente tipada e baseada em classe. Normalmente é compilado em bytecode e no formato binário definido na especificação da Java Virtual Machine (JVM).

Se você ainda não conhece Java, é legal passar por alguns tutoriais para se familiarizar com a linguagem.

Nos links abaixo encontrará o tutorial oficial da Oracle, mais um tutorial completo, um curso e um tutorial interativo para você praticar (faça apenas os tópicos grátis).

Referências em inglês:

- https://javabeginnerstutorial.com/core-java-tutorial/
- https://www.codecademy.com/learn/learn-java
- https://www.udemy.com/course/java-the-complete-java-developer-course/
- https://docs.oracle.com/javase/tutorial/index.html

Referências em português:

- https://www.caelum.com.br/apostila-java-orientacao-objetos/
- https://www.zup.com.br/blog/java

## Um pouco mais de Java

Agora que você já sabe o básico da linguagem, listamos aqui 5 características do Java que são essenciais no dia a dia:

1) Exceções - fluxo de controle para tratamento de erros
2) Anotações - extensões declarativas do programa
3) Programação Genérica - mecanismos para reutilizar código para vários tipos
4) Programação Funcional - mecanismos para tratar funções como dados
5) Beans - padrão para construção de componentes reutilizáveis

Nos anexos foram selecionados tutoriais focados em cada um dos itens acima listados.

Referências em inglês:

- https://www.tutorialspoint.com/java/java_exceptions.htm
- https://www.baeldung.com/java-chained-exceptions
- https://docs.oracle.com/javase/tutorial/java/annotations/index.html
- https://docs.oracle.com/javase/tutorial/java/generics/index.html
- https://docs.oracle.com/javase/tutorial/extra/generics/index.html
- https://www.baeldung.com/java-8-functional-interfaces
- https://www.baeldung.com/java-8-streams-introduction
- https://www.baeldung.com/java-8-streams

Referências em português:

- https://www.devmedia.com.br/tratando-excecoes-em-java/25514
- https://www.devmedia.com.br/usando-generics-em-java/28981

## Aprofundando Java

Não precisa se importar com os conceitos mais complexos no momento, mas é sempre bom saber onde procurar quando precisar.

Esse site em inglês [Geeks For Geeks](https://www.geeksforgeeks.org/java/) traz conceitos básicos até mais avançados e pode ser útil para entender o que significam alguns termos que poderão precisar entender mais para frente.

## Beans

Java Beans é um padrão do Java para construção de componentes reutilizáveis que é importante conhecer.

Seguem algumas referências para entender mais a respeito.

Referências em português:

- https://www.devmedia.com.br/introducao-aos-javabeans/8621
- https://docs.jboss.org/weld/reference/1.1.5.Final/pt-BR/html/intro.html

## Gerenciador de dependências

Ao construir uma aplicação, é comum ter várias peças para compilar e empacotar, tanto próprias quanto de terceiros (bibliotecas). O Maven é muito utilizado porque permite organizar essas peças declarativamente e te ajuda a gerenciar bibliotecas.

Nos anexos há 2 tutoriais: um pragmático e um profundo. Neles você encontrará mais detalhes sobre o uso da ferramenta.

Para praticar, utilize o link do Github (maven-examples do site mkyong) que possui um projeto simples de exemplo.

Referências em inglês:

- https://github.com/mkyong/maven-examples/tree/master/java-project
- https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html

Referências em inglês:

- https://www.devmedia.com.br/introducao-ao-maven/25128

## SQL

SQL é uma linguagem padrão para trabalhar com bancos de dados relacionais... A linguagem SQL é utilizada de maneira relativamente parecida entre os principais bancos de dados relacionais do mercado: Oracle, MySQL, MariaDB, PostgreSQL, Microsoft SQL Server, entre muitos outros.

Referências em português:

- https://www.devmedia.com.br/entedendo-a-linguagem-sql/7775
- https://www.devmedia.com.br/guia/guia-completo-de-sql/38314
- https://playcode.com.br/banco-de-dados/sql-banco-dados-iniciantes/

## Persistência com JDBC

O Back-End é responsável por gerenciar os dados de um sistema. E vários desses dados precisam ficar guardados por tempo indefinido. Para garantir isso, é necessário usar mecanismos de persistência. Hoje o predominante é o uso de tecnologias de banco de dados, principalmente bancos relacionais baseados na linguagem SQL.

Na biblioteca do Java, há o JDBC para fazer a comunicação com banco de dados.

Nos anexos, há um tutorial interativo do básico, outro mais avançado e um curso completo de SQL. Também tem um tutorial de JDBC.

Referências em inglês:

- https://www.learnsqlonline.org/
- https://www.tutorialspoint.com/sql/index.htm
- https://docs.oracle.com/javase/tutorial/jdbc/index.html
- https://medium.com/@s.brianryu/how-to-crud-in-sql-basic-sql-to-know-f8a0a486d41b

Referências em português:

- https://www.devmedia.com.br/guia/guia-completo-de-sql/38314
- https://www.caelum.com.br/apostila-java-web/

## Concorrência

Para usar melhor o poder computacional disponível hoje, há a programação concorrente. No fundo ela visa permitir que o programa faça várias coisas possivelmente ao mesmo tempo. Mas com isso, também surgem problemas que precisam ser pensados e tratados para que o programa funcione como esperado.

A biblioteca do Java fornece várias mecanismos para construção de programas concorrentes e para tratar os problemas comuns.

No material anexo, há um material mostrando os mecanismos de concorrência em Java.

Referências em inglês:

- https://docs.oracle.com/javase/tutorial/essential/concurrency/index.html

Referências em português:

- https://www.devmedia.com.br/java-8-conheca-os-recursos-para-a-programacao-concorrente/39298

## Servlets

Para um sistema Back-End ser usado, ele precisa ser acessado através da rede. Para isso, o protocolo HTTP é o predominante hoje.

A biblioteca do Java oferece os Servlets como mecanismo básico para construção de programas usando HTTP.

Nos anexos há tutoriais e cursos sobre HTTP e Servlets.

Referências em inglês:

- https://www.tutorialspoint.com/http/index.htm
- https://www.udemy.com/course/http-hypertext-transfer-protocol/
- https://www.tutorialspoint.com/servlets/index.htm
- https://kotlinlang.org/docs/server-overview.html

## DESAFIO 1: Crie um repositório para seu projeto

Acesse o Github e crie um projeto para a linguagem que escolheu (Java ou Kotlin).

Adicione um arquivo `README` na criação e um arquivo `.gitignore`.

## DESAFIO 2: CRUD de clientes

No mundo de Back-End, há quatro operações muito comuns a serem implementadas: criar, ler, atualizar e deletar, que compõem a sigla inglesa CRUD.

Escreva um programa (Java ou Kotlin) que implemente essas quatro operações para os dados de um cliente, salvando-os em uma estrutura de dados em memória. Crie uma interface textual ou gráfica para as operações.

Um cliente deve ter cadastrado pelo menos os seguintes dados:

- nome,
- CPF,
- e-mail,
- data de nascimento.

- A criação deve popular o cadastro de um cliente e inserir ele na estrutura.
- A leitura deve permitir visualizar todos os clientes ou um só pelo CPF.
- A atualização deve permitir alterar um ou mais dos dados de um cliente a partir do CPF dele (esse campo não pode ser alterado).
- A deleção deve permitir retirar um cliente da estrutura pelo CPF dele.

**Como entrega dessa atividade, me envie o link do repositório criado (LinkedIn ou email).**

## Bônus

Se achou esse segundo desafio fácil, você pode continuar melhorando essa implementação seguindo as sugestões deste [outro repositorio de treinamento](https://github.com/GuillaumeFalourd/java-training-api).
