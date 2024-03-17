# ADR: Permissions

# Authors

Joao Radicchi, Fabiano Miranda, Lucas Dayan, Diogo Carbone

# Date

2024-03-17

## Status

Accepted

## Context

As part of the development of the mobile app for the retail company, we need to consider the permissions required by the app to function properly and provide a seamless user experience. Permissions are necessary to access certain device features and data, and they play a crucial role in ensuring the app's functionality and security.

## Decision

We will implement the following permissions in the mobile app:

1. Internet Access: The app requires permission to access the internet to sync data with the server, send push notifications, and facilitate online transactions.

2. Network State: The app needs permission to check the network state to determine if the device is connected to the internet or in offline mode. This will allow the app to provide appropriate functionality and user experience in both scenarios.

3. Storage Access: The app requires permission to access the device's storage to store and retrieve data, including product images, order history, and user preferences.

4. Location Access: The app may require permission to access the device's location to provide location-based services, such as displaying nearby stores or offering personalized recommendations based on the user's location.

5. Camera Access: The app may require permission to access the device's camera to enable features such as barcode scanning for product search or capturing images for profile pictures.

6. Push Notification Access: The app needs permission to receive push notifications from the push notification service to deliver timely updates, offers, and order status notifications to the users.

## Consequences

By implementing these permissions, we ensure that the app can provide the desired functionality and user experience. However, it is important to handle these permissions responsibly and respect user privacy. We will follow best practices for permission handling, including requesting permissions only when necessary, providing clear explanations for why the permissions are required, and allowing users to manage and revoke permissions as needed.
