# Countries Cities MCP Server

## Overview

The Countries Cities MCP server provides comprehensive geographical data about countries and cities worldwide. It offers a range of functions that return various details such as latitude, longitude, languages, currency, timezone, population, and geoJSON data of countries and cities. This server is designed to help developers and data enthusiasts access detailed location-based information efficiently.

## Features

- **Comprehensive Geographical Data**: Obtain detailed information about countries and cities, including location, timezone, population, currency, and more.
- **GeoJSON Support**: Access geographical boundaries in GeoJSON format for advanced mapping and visualization.
- **Pagination for Cities**: Results for city data are paginated, with a maximum of 100 cities returned per page.
- **Freemium Model**: Offers a free tier with a limit of 1 request per second, suitable for development and small-scale applications.

## Tools

### Countries List
- **Description**: Returns a list of all countries along with their respective country codes.
- **Usage**: Ideal for applications requiring a comprehensive list of countries for selection or display.

### Country Details
- **Description**: Provides detailed information about a specific country, including its capital, location, timezone, population, currency, languages, and phone code.
- **Usage**: Useful for applications needing in-depth country-specific data.

### Country GeoJSON
- **Description**: Returns the geographical boundaries of a country in GeoJSON format.
- **Usage**: Suitable for applications involving mapping and geographical visualizations.

### Cities in the Country
- **Description**: Retrieves a list of cities within a specified country. Supports filtering by population, with a default threshold of cities having a population greater than 15,000.
- **Usage**: Useful for applications focusing on urban data analysis.

### Cities Nearby
- **Description**: Provides a list of cities in proximity to a given location, with options to filter by population size and radius.
- **Usage**: Ideal for location-based services and applications needing nearby city information.

### City Details
- **Description**: Offers detailed information about a specific city, including its geographical location and other relevant data.
- **Usage**: Useful for applications that require precise city-specific information.

## Conclusion

The Countries Cities MCP server is a versatile tool for accessing detailed geographical data about countries and cities. With its range of features and tools, it is an invaluable resource for developers and data professionals looking to build location-aware applications. Whether you need basic country lists or detailed city information, this server has you covered.