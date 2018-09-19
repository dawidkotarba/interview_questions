# Platform
- Describe a build system in Hybris? What does happen during build, init, update?
- What type of interceptors do you know that work with model in Hybris?
- Describe the event system in Hybris
- How to import data into Hybris?
- Describe how CMS is implemented in Hybris.
- What are restrictions in Hybris?
- Hybris provides a validation framework. How does it work?
- Hybris uses Spring to create application/web contexts. Describe what level of contexts do we have in Hybris and what is the hierarchy of them.

# Commerce
- What are catalogs in Hybris? Why do we need them? What types of catalogs do you know? What types are catalog-aware?
- Describe the concept of add-ons? Why we need them?
- Have you ever worked with order fulfillment? What steps are needed to modify the order fulfillment?
- What warehouse strategies do you know?
- Hybris offers several "hooks" that you can use to perform a business logic. What type of hooks do you know?
- Describe for what the Solr server is used. What are partial/full updates? Where the Solr is hit during browsing the storefront? What are Solr cores?

# Not classified
1. What are the necessary software layers in a hybris application? (DAO, Service, Facade, Controller)?
2. What do you use for populating data and converting between models and DTOs? (populator and converter)
3. Do you call the populator directly in the code?
4. What is the proper way to define a DTO? (define in xml)
5. How do you define data types/entites in Hybris? (items.xml)
6. How do you define collections in items.xml?
7. How do you define relations between models? (items.xml)
8. What do you use to define email templates in Hybris? (velocity template)
9. Which mode is used in transactions in Hybris? (READ_COMMITED)?
10. How to add new sample data to the Accelelator? (via impex)
11. You want to have optional impexes in HAC update. How do you implement it? (core system setup, impex)
12. What is the naming convention for a table containing localizable attributes? (lp suffix)
13. What is deployment tag for in items.xml? (defining a table for your type)
14. What happens if you don't define a deployment table for a new type?
15. Can you nest transactions in hybris? (transactions are merged into one)
16. How can you run a cronjob defined in hybris? (backoffice, ant runcronjob)
17. Explain the difference between dynamic and non-dynamic enums in Hybris.
18. How do you define a new top navigation bar?
19. What are content slots and components?
20. Name the types of content slots? (for page, for template)
21. What is the difference between ant all and ant clean all?
22. Which build system is used by Hybris?
23. What is HMC?
24. What is Backoffice?
25. Explain the hierarchy between basestore and storefront.
26. How many storefronts can have a single hybris instance?
27. What is used for importing data in Hybris? (impex importer, spring integration)
28. Explain what is impex.
29. What does ant initialize do?
30. How do you prepare your local hybris instance for unit tests? (ant yunitinit)
31. What are tenants in Hybris?
32. What are @UnitTest and @IntegrationTest annotations for?
33. What is Jalo layer in Hybris and should you use it?
34. What is ServiceLayer in Hybris?
35. What are catalog versions in hybris?
36. Name a few types whch are catalog aware.
37. How are media stored in Hybris?
38. Which framework is used for indexation in Hybris?
39. What is an index in Hybris?
40. What are solr cores and what types of cores there are?
