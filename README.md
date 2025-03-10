## e-wallet 
A full stack web app with React and Spring Boot is used to manage digital wallets and transactions.

<br/>

<img src="backend/src/main/resources/docs/images/dashboard.png" width="1060"/>

<br/>

<img src="backend/src/main/resources/docs/images/wallets.png" width="1060"/>
<br/>

### Description
This application allows users to implement an e-wallet with a REST API to create an account, top it up, check the balance, and withdraw money. 
Users can register and log in using the credentials. They can also add any wallets for any account provided by IBAN 
and transfer to their wallet plus any other wallet defined in the system.

The application has custom IBAN validators, which can easily be applied to any IBAN field via annotation as shown:

```
@ValidIban(msg = "{iban.valid}")
private String iban;
```

<br/>

<img src="backend/src/main/resources/docs/images/transactions.png" width="1060"/>

<br/>

<img src="backend/src/main/resources/docs/images/transfers.png" width="1060"/>

<br/>

### Architecture

The relationship between the entities is shown on this Architecture <img src="backend/src/main/resources/docs/architecture.png" width="1060"/>
<br/>

### Getting Started

To run and test application, see details on [How to run?](backend/src/main/resources/docs/how_to_run.md) and [How to test?](backend/src/main/resources/docs/how_to_test.md) sections.

<br/>

### Dependencies

* Spring Boot
* Spring-Web
* Spring Security
* Spring Data JPA
* Lombok 
* MapStruct
* PostgreSQL
* Flyway
* React
* Node.js
* MaterialUI

<br/>

### Documentation
[Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)<br/>
[Spring Security](https://docs.spring.io/spring-security/reference/index.html)<br/>
[Spring Data JPA](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)<br/>
[springdoc-openapi v2](https://springdoc.org/v2/)<br/>
[MapStruct](https://mapstruct.org/)<br/>
[JUnit 5](https://junit.org/junit5/docs/snapshot/user-guide/)<br/>
[Entity Relationship Diagram (ERD)](https://www.lucidchart.com/pages/er-diagrams)<br/>
[React](https://react.dev/)<br/>
[Material UI](https://mui.com/)<br/>
[Notistack](https://notistack.com/features/basic)<br/>
[Register of countries using the IBAN standard](https://www.iban.com/structure)<br/>

<br/>

### Version History 

* v1.0 Initial Release base

<br/>
<br/>
