# Weather Monitor

**Weather Monitor** is a Spring Boot application that provides weather monitoring functionality through RESTful APIs. It fetches weather data from the OpenWeatherMap API and allows users to store and retrieve this information in a MySQL database.

## Project Overview

This application allows users to monitor weather data by providing endpoints to retrieve current weather conditions. It utilizes Spring Boot for the back end, MySQL for data storage, and OpenWeatherMap for fetching live weather data.

## Technologies Used

- **Spring Boot**: Version 3.3.4
- **Java**: Version 17
- **MySQL**: Version 8.0
- **Maven**: Version 3.8.5
- **HikariCP**: Connection pool for efficient database access
- **OpenWeatherMap API**: For fetching weather data
- **JUnit & Mockito**: For testing (via Spring Boot Starter Test)
- **JSON Processing**: `org.json:json:20230227`

## Installation

1. Clone the repository :
   ```bash  git clone https://github.com/JivanRathod111/Weather-Application.git

2. Set up the MySQL database:

Create a new database in MySQL (e.g., weatherdata).
Update the src/main/resources/application.properties file with your database connection details (see Configuration section)


Conclusion

This README file provides comprehensive documentation for your Weather Monitoring Application, guiding users through setup, configuration, and usage. If you have any more requests or need further assistance, feel free to ask!
