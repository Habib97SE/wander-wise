# Wander Wise 

Wander Wise is a travel app that helps users plan their trips by providing them with information about the weather, currency exchange rates, routes, gas stations along the way, and more.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Features
- Users can create a trip, add stops to the trip, and view the stops on a map (as a highlighted route).
- Users can view the weather forecast for each stop on the trip.
- Users can view the currency exchange rates for each stop on the trip.
- Users can view the gas stations along the route.
- Users can add a playlist to the trip.
- Users can add Todo items to the trip (the items that should be done, e.g. buy a ticket, book a hotel, etc.).
- Users can add ToPack items to the trip (the items that should be packed, e.g. clothes, shoes, etc.).
- Users can add highlights to the trip (this feature is like a diary, where users can add notes, photos, etc.).
- Users can view the trip summary (the total distance, the total duration, the total cost, etc.).



## Installation
To install the app, you can clone the repository by running the following command in your terminal:
```bash
git clone https://github.com/Habib97SE/wander-wise.git
```

And then inside the frontend folder, run the following command to install the dependencies:
```bash
npm install
```

In the backend folder, run the following command to install the dependencies:
```bash
mvn install
``` 

You need to add the following environment variables to your system:
- `DB_URL`: The URL of the database
- `DB_USERNAME`: The username of the database
- `DB_PASSWORD`: The password of the database
- `GOOGLE_API_KEY`: The API key for the Google Maps API
- `SPOTIFY_CLIENT_ID`: The client ID for the Spotify API

## Usage
To use the app, you can run the following command in the frontend folder:
```bash
npm start
```

And then in the backend folder, run the following command:
```bash
mvn spring-boot:run
```

## Technologies Used
- For the frontend, we used:
    - React
    - Tanstack Router & Query

- For the backend, we used:
    - Java 17+
    - Spring Boot
    - Hibernate
    - PostgreSQL 16


## Contributing
To contribute to the project, you can fork the repository and create a pull request. We will review the pull request and merge it if it is approved.

