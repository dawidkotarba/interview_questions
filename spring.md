# Spring Interview Questions

## Core Concepts & Dependency Injection
- What is Dependency Injection (DI)? How does it differ from Inversion of Control (IoC)?
- What are common stereotype annotations in Spring? (@Component, @Service, @Controller, @Repository).
- What is the difference between @Bean and @Component? When to use each?
- When do we need aliasing of beans in Spring?
- What are Spring bean scopes? (singleton, prototype, request, session, application, websocket).
- Can we inject a prototype bean into a singleton? How can we handle this (lookup method, ObjectFactory, Provider, scoped proxy)?
- What is @Lazy? What are its use cases?
- What is @Autowired vs @Resource? How do they differ?
- What is the role of @Qualifier in autowiring?
- How can we inject dependencies in Spring? (XML, constructor injection, field injection, setter injection).
- What is the difference between constructor injection and field/setter injection? (e.g., null safety in constructors).
- What happens if beanA injects beanB and beanB injects beanA (circular dependency)? Will the context start? How can it be fixed?
- BeanFactory vs ApplicationContext – differences.
- BeanFactoryPostProcessor vs BeanPostProcessor – what is the difference and when to use each?
- What is ApplicationContextAware? What are its use cases?
- Difference between JDK proxy, CGLIB proxy, and AspectJ proxy.
- AspectJ compile-time weaving vs runtime proxy.
- What are profiles in Spring? How can we use them?

## Spring AOP
- What is Aspect-Oriented Programming (AOP)?
- What are the main concepts: Aspect, Join Point, Advice, Pointcut, Weaving?
- Types of advice: @Before, @After, @AfterReturning, @AfterThrowing, @Around.
- How does Spring implement AOP under the hood (dynamic proxies, CGLIB)?
- What are common use cases for AOP? (logging, transactions, security).
- What are limitations of Spring AOP compared to full AspectJ?

## Transactions in Spring
- What is @Transactional? How does it work internally?
- Transaction propagation types in Spring (REQUIRED, REQUIRES_NEW, MANDATORY, SUPPORTS, NOT_SUPPORTED, NEVER, NESTED).
- Transaction isolation levels in Spring. Which anomalies do they prevent? (dirty reads, non-repeatable reads, phantom reads).
- How can we roll back a transaction? (rollbackFor, RuntimeException vs checked Exception).
- How are transactions managed in Spring Boot by default?
- What happens if a @Transactional method is called from within the same class (self-invocation problem)?

## Spring MVC
- What is the DispatcherServlet? Describe the general architecture of Spring MVC.
- What is the Front Controller pattern and how does Spring MVC implement it?
- What are HandlerMappings, Controllers, and ViewResolvers?
- What are @RequestMapping, @GetMapping, @PostMapping? Differences?
- What are @RequestParam, @PathVariable, and @RequestBody? Use cases?
- How does Spring handle form validation (JSR-303, @Valid, @Validated)?
- How does exception handling work in Spring MVC? (@ExceptionHandler, @ControllerAdvice, ResponseEntityExceptionHandler).
- How does Spring handle file upload?

## Spring Boot
- What is Spring Boot? How does it differ from Spring Framework?
- What are the advantages of using Spring Boot?
- What application servers are shipped with Spring Boot (Tomcat, Jetty, Undertow)? What are their pros/cons?
- How does auto-configuration work in Spring Boot? What is @EnableAutoConfiguration?
- What is Spring Boot Starter? Examples of common starters.
- What is Spring Boot Actuator? What features does it provide?
- How does Spring Boot manage configuration (application.properties, application.yml, profiles)?
- How to override default properties in Spring Boot?
- How does Spring Boot handle externalized configuration (environment variables, command-line args, config server)?
- What is Spring Boot DevTools?
- How does Spring Boot support microservices (Spring Cloud, Config Server, Service Discovery)?

## Spring Data
- What is Spring Data JPA? How does it simplify repository layer?
- What are CrudRepository, PagingAndSortingRepository, JpaRepository?
- How does method name parsing work in Spring Data (e.g., findByNameAndAgeGreaterThan)?
- How to write custom queries in Spring Data (JPQL, @Query)?
- How to use projections (DTO-based, interface-based)?
- What is optimistic vs pessimistic locking in Spring Data?
- What is auditing in Spring Data (@CreatedDate, @LastModifiedDate)?
- How does pagination and sorting work in Spring Data?

## Security (Spring Security)
- What is Spring Security? What problems does it solve?
- Difference between authentication and authorization.
- How does Spring Security integrate with servlet filters?
- What are common authentication providers (in-memory, JDBC, LDAP, OAuth2)?
- How does method-level security work (@PreAuthorize, @PostAuthorize)?
- What is CSRF and how does Spring Security handle it?
- How does Spring Security integrate with JWT?
- What are password encoders in Spring Security (BCrypt, PBKDF2, SCrypt)?
