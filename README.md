# Parallel Web Crawler

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Java Version](https://img.shields.io/badge/Java-1.8+-blue.svg)
![Spring Boot Version](https://img.shields.io/badge/Spring%20Boot-2.x-brightgreen.svg)

## Overview

The Parallel Web Crawler is a high-performance, multithreaded web crawler built using Java and Spring Boot. This web crawler is designed to index websites concurrently, making the data collection process significantly faster.

## Features

- Multithreaded crawling using Java's Concurrency API.
- Built with Spring Boot for easy setup and configuration.
- Highly scalable, capable of crawling hundreds of websites concurrently.
- User-configurable settings for depth and number of threads.

## Prerequisites

- Java 1.8 or higher
- Maven
- Spring Boot 2.x

## Installation

1. Clone the repository
   ```
   git clone https://github.com/binay-shah/Parallel-Web-Crawler.git
   ```
  
2. Navigate to the project directory
   ```
   cd Parallel-Web-Crawler
   ```

3. Build the project
   ```
   mvn clean install
   ```

4. Run the application
   ```
   java -jar target/ParallelWebCrawler-0.0.1-SNAPSHOT.jar
   ```

## Usage

Modify the `application.properties` file to set the crawling parameters like starting URL, maximum depth, and number of threads.

```properties
crawler.startURL=https://example.com
crawler.maxDepth=5
crawler.maxThreads=10
```

Run the application, and the crawled URLs will be saved in a specified file or database (based on your implementation).

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
