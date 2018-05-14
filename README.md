Vitaly Pobokin (Виталий Побокин)

pbk.vitaliy@gmail.com

Project #1
Description: Corporative page with frontend built upon AngularJS and JAX-RS REST API on the backend. Available CRUD operations and additional filtering for Employee and Department entities. JWT-token authentication with a different access level. Admin page with different statistics markers presented as charts.
Technologiesa : AngularJS, Bootstrap, JWT, Servlet, Jersey, Jackson, Jsoup, JPA, Ehcache, Hibernate, OracleDB
Languages: Java, JavaScript, SQL, HTML
Environment: Tomcat, OracleXE

Project #2
Description: Web chat with functionality to log in, register, sending messages to other connected clients through WebSocket protocol and persisting sent messages in DB. Microservice-like architecture with next modules:
•    Frontend-service (2 modules on different ports): Angular5, JSR-356 WebSocket implementation on embedded Jetty and messaging system over Socket to send a request and receive responses to log in, register users and persisting chat-messages
•    User-service: handling requests to authorize and register user. Uses Hibernate framework and PostgreSQL. Sent responses to frontend-service to indicate successful or failed authorization/registration
•    Chat-message service: handling requests to persist chat messages. Uses Hibernate framework and PostgreSQL
•    Message-service: manages messages between different services
Technologies: Angular, WebSockets, Jetty, Guice, Jackson, Sockets, Hibernate, PostgreSQL
Languages: Java, TypeScript, SQL, HTML
Environment: Embedded Jetty, JRE, PostgreSQL

Project #3
Description: Online Store. Frontend part was made with usage of JSF and Bootfaces. Realized shopping cart functionality for which is used SessionScoped beans. By clicking "Buy" button shopping cart content could be persisted in DB as an order. Before committing an order you should be registered and logged in. User credentials are also persisting in DB.
Technologies: JSF, EJB, CDI, Jackson, Hibernate, OracleDB
Languages: Java, SQL, HTML
Environment: Glassfish, OracleXE