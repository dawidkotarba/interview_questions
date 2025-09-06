# Maven Interview Questions

## Dependency Management
- What are the different scopes of dependencies in Maven (compile, provided, runtime, test, system)?
- What is the meaning of the `-SNAPSHOT` suffix in Maven versions?
- What are transitive dependencies and how does Maven handle them?
- How do you exclude a transitive dependency?
- How can you override dependency versions defined in parent POMs?

## Build Lifecycle
- What is the Maven build lifecycle? Describe the default phases.
- What is the difference between `install` and `deploy` phases?
- What does the `mvn install` command do specifically?
- How do you customize or overrule default Maven phase behavior?
- How do you run a specific lifecycle phase in Maven?
- What are goals in Maven, and how are they associated with phases?

## Project Object Model (POM)
- What elements can you define in a parent POM?
- How do you inherit properties and dependencies from a parent POM?
- How do you define modules in a multi-module Maven project?
- How do you manage versions of dependencies across modules?

## Packaging & Artifacts
- How do you package a project into a JAR, WAR, or ZIP file?
- How do you attach additional resources or artifacts to the build?
- How can you generate site documentation using Maven?

## Additional/Common Questions
- How do you list all dependencies of a project (`mvn dependency:tree`)?
- How do you handle conflicts between dependency versions?
- How do you use Maven profiles and what are common use cases?
- How can you configure Maven to build differently for dev, test, and production environments?
- How do you integrate Maven with CI/CD pipelines (Jenkins, GitHub Actions, etc.)?
