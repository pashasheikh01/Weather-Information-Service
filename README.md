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

![Current Weather](images/current-weather.png)

Displays current weather information for a selected city.

### Weather Comparison

![Weather Comparison](images/weather-comparison.png)

Compares weather conditions between two cities.

### Automated Testing

![Automated Testing](images/weather-tests.png)

JUnit tests used to verify the application's functionality.
