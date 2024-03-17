# ADR: Prisma as ORM for Mobile App Development

# Authors

Joao Radicchi, Fabiano Miranda, Lucas Dayan, Diogo Carbone

# Date

2024-03-17

## Status

Accepted

## Context

We are developing a mobile app for a retail company that requires a robust and efficient Object-Relational Mapping (ORM) solution. The ORM will be responsible for handling database operations and providing an abstraction layer between the app and the underlying database.

## Decision

After evaluating various ORM options, we have decided to use Prisma as our ORM for the mobile app development. Prisma is a modern and powerful ORM that offers several advantages:

1. **Type-safe queries**: Prisma provides a type-safe query API that allows us to write database queries using TypeScript. This helps catch errors at compile-time and provides better code completion and documentation.

2. **Database agnostic**: Prisma supports multiple databases, including PostgreSQL, MySQL, and SQLite. This flexibility allows us to choose the database that best suits our app's requirements.

3. **Performance**: Prisma uses a highly optimized query engine that generates efficient SQL queries. This helps improve the app's performance and reduces the load on the database.

4. **Schema migrations**: Prisma provides a migration tool that allows us to manage database schema changes easily. This ensures that our database schema stays in sync with the app's evolving requirements.

5. **Real-time data synchronization**: Prisma supports real-time data synchronization through its subscriptions feature. This enables us to build real-time features such as live updates and notifications.

## Consequences

By choosing Prisma as our ORM, we can leverage its features and benefits to develop a scalable, performant, and maintainable mobile app. However, there are a few considerations to keep in mind:

1. **Learning curve**: The team will need to familiarize themselves with Prisma's query API and migration tool. Training and documentation resources should be provided to ensure a smooth transition.

2. **Community support**: Prisma has a growing community and active development, but it may not have the same level of community support as more established ORMs. The team should be prepared to rely on official documentation and forums for assistance.

3. **Compatibility**: Prisma's compatibility with other libraries and frameworks used in the app should be evaluated. Integration with other tools, such as authentication and authorization libraries, should be considered during the development process.

Overall, we believe that Prisma is a suitable choice for our mobile app development, considering its features, performance, and flexibility.
