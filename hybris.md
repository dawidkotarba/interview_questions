# Hybris Interview Questions

## Platform
- Describe the build system in Hybris. What happens during build, init, and update?
- What type of interceptors do you know that work with models in Hybris?
- Describe the event system in Hybris.
- How do you import data into Hybris?
- How is CMS implemented in Hybris?
- What are restrictions in Hybris?
- Hybris provides a validation framework. How does it work?
- Hybris uses Spring to create application/web contexts. What levels of contexts exist in Hybris and what is their hierarchy?
- What is the difference between dynamic and non-dynamic enums in Hybris?

## Commerce
- What are catalogs in Hybris? Why do we need them? What types of catalogs exist? Which catalogs are catalog-aware?
- Describe the concept of add-ons. Why do we need them?
- Have you worked with order fulfillment? What steps are needed to modify it?
- What warehouse strategies do you know?
- Hybris offers several "hooks" to perform business logic. What types of hooks exist?
- Describe Solr in Hybris: What is it used for? What are partial/full updates? When is Solr queried during storefront browsing? What are Solr cores?

## Core & Architecture
- What are the necessary software layers in a Hybris application (DAO, Service, Facade, Controller)?
- How do you populate data and convert between models and DTOs? (populator and converter)
- Do you call the populator directly in code?
- What is the proper way to define a DTO? (define in XML)
- How do you define data types/entities in Hybris? (items.xml)
- How do you define collections in items.xml?
- How do you define relations between models? (items.xml)
- What do you use to define email templates in Hybris? (velocity templates)
- Which transaction mode is used in Hybris? (READ_COMMITTED)
- Can you nest transactions in Hybris? How are nested transactions handled?
- What is the Jalo layer in Hybris and should you use it?
- What is the ServiceLayer in Hybris?

## Cronjobs & Testing
- How can you run a cronjob defined in Hybris? (Backoffice, ant runcronjob)
- How do you prepare your local Hybris instance for unit tests? (ant yunitinit)
- What are @UnitTest and @IntegrationTest annotations for?

## Frontend & CMS
- How do you define a new top navigation bar?
- What are content slots and components?
- Name the types of content slots (for page, for template).
- Explain the hierarchy between basestore and storefront.
- How many storefronts can a single Hybris instance have?

## Deployment & Impex
- What is used for importing data in Hybris? (impex importer, Spring integration)
- Explain what is an impex.
- How do you add new sample data to the Accelerator? (via impex)
- How would you implement optional impexes in HAC update? (core system setup, impex)
- What is the naming convention for a table containing localizable attributes? (lp suffix)
- What is the deployment tag in items.xml used for?
- What happens if you don't define a deployment table for a new type?

## Build System & Tools
- What is the difference between ant all and ant clean all?
- Which build system is used by Hybris?
- What does ant initialize do?

## Catalogs & Media
- What are catalog versions in Hybris?
- Name a few types that are catalog-aware.
- How are media stored in Hybris?

## Indexing & Search
- Which framework is used for indexation in Hybris?
- What is an index in Hybris?
- What are Solr cores and what types of cores exist?
