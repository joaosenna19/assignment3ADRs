# ADR for UI Framework

# Authors

Joao Radicchi, Fabiano Miranda, Lucas Dayan, Diogo Carbone

# Date

2024-03-17

## Status

Accepted

## Context

We need to select a UI framework for developing the mobile app for the retail company. The UI framework should provide a set of pre-built components and tools to streamline the development process and ensure a consistent and visually appealing user interface.

## Decision

After evaluating various options, we have decided to use React Native as the UI framework for the mobile app. React Native is a popular framework that allows us to build native mobile apps using JavaScript and React. It provides a rich set of UI components, a fast development cycle, and excellent performance.

## Rationale

Here are the reasons for choosing React Native as the UI framework:

1. Cross-platform compatibility: React Native allows us to write code once and deploy it on both iOS and Android platforms, saving development time and effort.

2. Native performance: React Native uses native components, which ensures that the app performs well and provides a native-like user experience.

3. Large community and ecosystem: React Native has a vibrant community and a vast ecosystem of libraries and tools, making it easier to find solutions to common problems and accelerate development.

4. Hot reloading: React Native's hot reloading feature allows us to see the changes in real-time, speeding up the development process and improving productivity.

5. Offline support: React Native provides libraries and tools for handling offline mode, allowing us to implement the retail company's requirement of supporting offline browsing and syncing data with the server.

## Consequences

Using React Native as the UI framework has the following consequences:

1. Learning curve: The development team may need to learn React Native and its associated tools and libraries if they are not already familiar with them.

2. Limited access to native APIs: While React Native provides access to many native APIs, there may be cases where we need to write custom native modules or use third-party libraries to access specific device features.

3. Performance trade-offs: While React Native provides excellent performance, there may be cases where complex animations or heavy computations require additional optimization.

4. Maintenance: React Native is an evolving framework, and updates may introduce breaking changes or require updates to the app's codebase.

Overall, we believe that the benefits of using React Native outweigh the potential drawbacks, and it is the best choice for developing the mobile app for the retail company.
