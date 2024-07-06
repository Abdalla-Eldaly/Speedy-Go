![Screenshot (121)](https://github.com/Abdalla-Eldaly/Speedy-Go/assets/145719680/c70f1e4e-47af-4adb-8127-aa050c1b45ee)
# Speedy Go


Speedy Go is a smart transportation application designed to streamline and enhance the user experience for both passengers and bus drivers. The app includes features such as distance and time calculations, emergency call functions, driver feedback, and more.

## Architecture
- **App Layer 📱**: The heart of our application where the main functionalities reside.
- **Data Layer 📲**: Handles data sources such as server APIs, Firebase, and Hive. Each database serves a unique purpose, such as authentication, caching, or offline access.
- **Domain Layer 🧠**: Contains the business logic and entities of the app, defining use cases and repositories that interact with the data layer.
- **Presentation Layer 🎨**: Manages the state and presentation of the app, using providers and consumers to update the UI according to data changes.

## Features
- **Authentication and Verification**: Users can sign up, log in, and verify their email and phone number.
- **Dynamic Pricing and Negotiation**: Passengers and drivers can set prices for trips and negotiate.
- **Multiple User Types**: Includes passengers, car drivers, tuk-tuk drivers, bus drivers, and a unique user type for bus drivers who can add buses and trips between cities.
- **Ticket Booking**: Passengers can book tickets for trips.
- **Data Management**: Users can view past and current trips and update personal information such as name, email, phone number, and photo.
- **Animations**: Enhanced user experience with smooth animations throughout the app.
- **Real-Time Tracking**: Track the location of vehicles in real-time for enhanced safety and convenience.
- **In-App Communication**: Passengers and drivers can communicate directly within the app to coordinate trips.
- **Ratings and Reviews**: Users can rate and review their trips, providing valuable feedback to improve service quality.
- **Emergency Assistance**: In-app emergency assistance feature for safety during trips.
- **Ride Sharing**: Option for passengers to share rides with others heading in the same direction, reducing costs and environmental impact.
- **Comprehensive Trip Management**: All users can view and manage past and current trips.
- **Bus Management**: Bus drivers can add buses and trips, and manage all their trips efficiently.

Developing Speedy Go has been an incredible learning experience, allowing me to delve into clean architecture and explore various essential packages. ❤️

## Installation
1. Clone the repository:
   ```bash
https://github.com/Abdalla-Eldaly/Speedy-Go.git
