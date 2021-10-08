# Spring

## Spring DI
- Component types (Service, Controller, Repository, etc.)
- JDK proxy vs CGLib proxy vs AspectJ proxy
- AspectJ compile time weaving vs runtime proxy
- Why to use @Bean annotation? @Bean vs @Component
- When do we need aliasing of beans in Spring?
- @Autowired vs @Resource
- @Qualifier in autowiring
- Spring beans scopes, web scopes
- Can we inject prototype into singleton? What is a lookup method or scoped proxy?
- BeanFactoryPostProcessor vs BeanPostProcessor. What is the difference and when to use each of these?
- How we can inject fields in Spring (xml, ctor injection, field and setter)
- What is the difference between ctor injection and i.e. field injection (nulls not allowed in ctor injection)
- What happens if i.e. beanA injects by ctor beanB and beanB injects beanA (so we have a cycle). Will the context start? How to fix such issue? (design issue but can be fixed by @Lazy)
- What is a good use case for @Lazy? What is @Lazy?

## Transactions in Spring
- Transaction isolation in Spring. What phenomenas each isolation prevents?
- Transaction propagation in Spring
- How can we rollback a transaction?

## Spring MVC
- What is a dispatcher servlet? Describe the general architecture of Spring MVC.

## Spring Boot
- Describe what application servers are shipped with Spring Boot (or what servers we can use for). What are advantages of them?
