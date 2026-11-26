# Weather Information Service

## Project Overview

The Weather Information Service is a Java-based command-line application that retrieves current weather information using the Open-Meteo API. Users can view weather conditions, compare different cities, generate weather summaries, and find the warmest city.

## Technical Skills

- Java
- REST API and JSON
- Maven
- JUnit
- Object-Oriented Programming
- Dependency Injection

## Development Process

The original application contained most of its functionality in a single file. I separated the application into different classes responsible for retrieving weather data, processing information, and handling user commands.

I also implemented a feature that allows users to find the warmest city among the available locations.

## Challenges and Testing

One of the main challenges was separating the application logic from the weather API. I used interfaces and dependency injection to make the application easier to maintain and test.

I also used JUnit to test the application's functionality without relying on the live weather API.

## Project Screenshots

### Current Weather

<img width="675" height="497" alt="Screenshot 2026-11-26 161641" src="https://github.com/user-attachments/assets/26f773b9-06de-4d54-bc6f-b253655fc5c0" />

Displays current weather information for a selected city.

### Weather Comparison

<img width="670" height="382" alt="Screenshot 2026-11-26 161811" src="https://github.com/user-attachments/assets/8ae42c0a-bdb2-422e-b71e-486efb017a58" />

Compares weather conditions between two cities.

### Automated Testing

<img width="1043" height="398" alt="Screenshot 2026-11-26 161712" src="https://github.com/user-attachments/assets/4b8e962d-e050-47a9-a0ca-fe3628640792" />

JUnit tests used to verify the application's functionality.
