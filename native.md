# ADR: Native, Web, or Hybrid App

# Authors

Joao Radicchi, Fabiano Miranda, Lucas Dayan, Diogo Carbone

# Date

2024-03-17

## Status

Accepted

## Context

We are developing a mobile app for a retail company that allows customers to browse and purchase products, view order history, track deliveries, and participate in a loyalty program. We need to decide whether to build a native, web, or hybrid app.

## Decision

After considering the requirements and constraints, we have decided to develop a native app for the following reasons:

1. Performance: Native apps are known for their superior performance compared to web or hybrid apps. This is crucial for providing a smooth and responsive user experience, especially when browsing products and making transactions.

2. Offline Mode: Native apps offer better support for offline mode compared to web apps. With native development, we can implement data synchronization with the server once an internet connection is available, allowing customers to browse products and view order history even without an internet connection.

3. Push Notifications: Native apps have better integration capabilities with push notification services, making it easier to deliver timely notifications to customers about order updates, new product arrivals, and exclusive offers.

4. Payment Gateways: Native apps provide more flexibility in integrating with various payment gateways. We can select and integrate a suitable payment gateway or a combination of gateways based on security, ease of use, and compatibility with the app's target platforms.

5. User Behavior Tracking: Native apps offer better support for tracking user behavior and integrating with analytics tools or services. This will help us gather detailed insights and metrics to improve the app's performance and user experience.

6. Image Optimization: Native apps allow us to implement image optimization techniques such as caching, lazy loading, and compression more effectively. This will ensure optimal performance when displaying product images of varying sizes and resolutions.

7. Localization: Native apps provide better support for localization, allowing us to easily implement multiple languages and adapt to various cultural preferences. We can leverage native localization frameworks or libraries to achieve this.

## Consequences

Developing a native app requires platform-specific development skills and may result in higher development costs compared to web or hybrid apps. However, the benefits of superior performance, offline mode support, push notifications, payment gateway integration, user behavior tracking, image optimization, and localization outweigh these considerations in our case.
