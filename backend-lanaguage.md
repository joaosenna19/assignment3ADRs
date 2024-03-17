# ADR: Backend Language Selection

# Authors

Joao Radicchi, Fabiano Miranda, Lucas Dayan, Diogo Carbone

# Date

2024-03-17

## Status

Accepted

## Context

We are developing a new mobile app for a retail company that requires a backend system to handle various functionalities such as product browsing, order management, and loyalty program features. We need to decide on the backend language for implementing the server-side logic.

## Decision

After considering various factors such as performance, scalability, community support, and compatibility with the app's target platforms, we have decided to use Node.js as the backend language for this project.

## Rationale

1. Performance: Node.js is known for its event-driven, non-blocking I/O model, which allows for high concurrency and scalability. This makes it suitable for handling a large number of concurrent requests, ensuring optimal performance for our app.

2. JavaScript Ecosystem: Node.js leverages the extensive JavaScript ecosystem, providing access to a wide range of libraries, frameworks, and tools. This allows for faster development, easier integration with frontend code, and better code reuse.

3. Community Support: Node.js has a large and active community of developers, which means there is a wealth of resources, documentation, and community-driven modules available. This ensures that we can find solutions to any challenges we may encounter during development.

4. Compatibility: Node.js is compatible with various platforms, including Windows, macOS, and Linux. This ensures that our backend code can be easily deployed and run on different environments, providing flexibility and ease of deployment.

5. Scalability: Node.js is designed to handle high levels of concurrency, making it suitable for scaling our backend system as our customer base grows. It also supports clustering and load balancing, allowing us to distribute the workload across multiple instances.

## Consequences

By choosing Node.js as the backend language, we can leverage its performance, JavaScript ecosystem, community support, compatibility, and scalability. However, it also means that our development team should have expertise in JavaScript and Node.js, and we need to ensure proper testing and optimization to maximize the benefits of this decision.
