<h2>Dio Bootcamp TQI - FullStack Developer</h2>
<h3>Desenvolvimento de testes unitários para validar uma API REST de gerenciamento de estoques de cerveja.</h3>

Nesse repositório foi criada uma API REST e diversos testes utilizando ferramentas aprendidas nas aulas para:
* Entender sobre testes unitários.
* Entender os principais frameworks para testes unitários.
* Desenvolver testes unitários para validação de funcionalidades básicas como:
  * Criação
  * Listagem
  * Consulta por nome
  * Exclusão

Para executar o projeto, basta compilar esse projeto no IntelliJ Idea e ele vai subir a API para ser usada com o Postman.

Com o Postman iniciado basta apenas abrir o seguinte endereço e visualizar a execução do projeto 
utilizando o postman
como os métodos POST configurado o body para raw do tipo json no endereço abaixo.

```
http://localhost:8080/api/v1/beers
```

Para testar a alteração de registros usei o método PATCH passando como parâmetro na url o id da cerveja e o método increment.

```
http://localhost:8080/api/v1/beers/3/increment
```

São necessários os seguintes pré-requisitos para a execução do projeto desenvolvido durante a aula:

* Java 18.
* Maven 3.6.3 ou versões superiores.

Abaixo, seguem links bem bacanas, sobre tópicos mencionados durante a aula:

* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
* [Site oficial Mockito](https://site.mockito.org/)
* [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
* [Referências - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Referência pirâmide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)



