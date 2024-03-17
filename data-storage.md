# ADR: Data Storage

# Authors

Joao Radicchi, Fabiano Miranda, Lucas Dayan, Diogo Carbone

# Date

2024-03-17

## Status

Accepted

## Context

We are developing a mobile app for a retail company that requires data storage to support various features such as browsing products, order history, and loyalty program. We need to select a suitable data storage solution that meets the requirements of the app.

## Decision

After evaluating different options, we have decided to use MongoDB as the data storage solution for the mobile app.

## Rationale

1. Flexibility: MongoDB is a NoSQL database that provides a flexible schema, allowing us to easily adapt to changing requirements and accommodate different data structures.

2. Scalability: MongoDB is designed to scale horizontally, making it suitable for handling large amounts of data and accommodating future growth of the retail company's customer base.

3. Offline Mode Support: MongoDB's built-in replication and synchronization capabilities enable us to implement offline mode support. The app can store data locally on the device and sync with the server once an internet connection is available.

4. Performance: MongoDB's document-based model and indexing capabilities provide efficient data retrieval and querying, ensuring optimal performance for browsing products and viewing order history.

5. Integration: MongoDB has a rich ecosystem of libraries and tools that can be easily integrated with the mobile app's development stack, simplifying the implementation and maintenance process.

## Consequences

By choosing MongoDB as the data storage solution, we can ensure flexibility, scalability, and performance for the mobile app. However, it requires additional effort for setting up and managing the database infrastructure. We need to consider the learning curve for developers who are not familiar with MongoDB and ensure proper backup and disaster recovery mechanisms are in place.
