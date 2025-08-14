# Weather-App
**Course:** Programming 2 (Programming Assignment Unit 8)  
**Student:** Alanood Binlaksar  
**Date:** 14 August 2025  

---

## Description  
This Java Swing-based application provides real-time weather information using the OpenWeatherMap API.  
Users can search for a city’s current weather, view a short-term forecast, and maintain a history of previous searches.  
The app dynamically adjusts its background to reflect day or night based on the city’s sunrise and sunset times.

---

## Features
- Search for current weather by city name.  
- Display temperature, humidity, wind speed, and weather conditions.  
- Displays the next 5 upcoming forecast intervals (covering ~15 hours ahead) with time, temperature, and weather conditions.
- Search history for quick access to previous queries.  
- Dynamic day/night background based on city time.

---

###  Prerequisites  
Before running the application, make sure you have the following installed:  

1. **Java Development Kit (JDK)** — Version 8 or later.  
   - [Download JDK](https://www.oracle.com/java/technologies/javase-downloads.html)  
2. **Internet Connection** — Required to fetch live weather data from the API.  
3. **OpenWeatherMap API Key** — Sign up for a free key at [OpenWeatherMap](https://openweathermap.org/api).  
4. **JSON Library JAR** — Required for parsing JSON responses. Download the latest `json-xxxxxx.jar` from the [Maven Repository](https://mvnrepository.com/artifact/org.json/json).

---

## How to Run

### 1. Compile the code
Open your terminal and compile the Java file:
```bash
javac WeatherApp.java
```


### 2. Run the application
After compiling, run the program using:
```bash
java WeatherApp
```

### 3. API Key Setup
1. Sign up at [OpenWeatherMap](https://openweathermap.org/api) to get your free API key.
2. Add the API key to the program where indicated in the code.

### 4. Install JSON Library (Required for Parsing) 
1. Download the [json-20210307.jar] (or latest version) from the [Mvn Repository](https://mvnrepository.com/artifact/org.json/json).
2. Place the JAR file in your project directory.
3. Compile your program including the JAR file in the classpath:
   ```bash
   javac -cp .;json-20210307.jar WeatherApp.java
   ```
4. Run the program with the JAR in the classpath:
   ```bash
   java -cp .;json-20210307.jar WeatherApp
   ```
   **Note**(For macOS/Linux, replace ; with : in the commands.)

