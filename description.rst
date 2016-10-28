What is NCQRS?
==============

The official answer is:

| Ncqrs is a framework for .NET helps build scalable, extensible and maintainable applications by supporting developers apply the Command Query Responsibility Segregation (CQRS) architectural pattern. It does so by providing an infrastructure and implementations for the most important building blocks for command handling, domain modeling, event sourcing, and so. These building blocks help you to focus on the code that adds business value. They come with annotation, convention and configuration support and help you to write isolated and testable.

| 

NCQRS is really a collection of design patterns and technology brought together to allow you to
easily and quickly build large scale and scalable applications.  They are:

Command Query Responsibility Segregation
----------------------------------------

Command Query Responsibility Segregation (CQRS) is a design pattern where, simply put, the parts of your application responsible for updating the state / data of the application is not the same part responsible for querying that state / data.  **The Command (write) is separate from the Query (read)**.

Features
--------

- Rich components to support a full CQRS architecture
- Command mapping
- Domain event mapping
- Event sourcing
- Service bus handling of commands and events for microservices architecture
- Event storage with MSSQL, Azure or MongoDB support
- Sample application
- A testing framework to test your events in isolation
- Easy to extend!