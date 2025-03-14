# Redis Cache Demo with Spring Boot

This project demonstrates how to use Redis as a caching solution with Spring Boot applications.

## Project Overview

The application showcases how to implement efficient caching strategies using Redis in a Spring Boot application. It demonstrates various Spring Cache annotations and their usage patterns.

## Features

- Redis integration with Spring Boot
- Cache-aside pattern implementation
- Various caching strategies (@Cacheable, @CachePut, @CacheEvict)
- RESTful API endpoints to demonstrate caching behavior

## Prerequisites

- JDK 17+
- Gradle
- Redis server (local installation or Docker)

## Getting Started

1. Start Redis server: 
   ```
   docker run --name redis -p 6379:6379 -d redis
   ```

2. Run the application:
   ```
   ./gradlew bootRun
   ```

3. Access the API at `http://localhost:8080`

## Project Structure

- `config`: Redis configuration classes
- `model`: Data models
- `repository`: Data access layer
- `service`: Business logic with caching
- `controller`: REST API endpoints

## Learning Outcomes

Through this project, you will learn:
- How Redis caching works with Spring Boot
- The cache-aside pattern implementation
- When and how to use different caching annotations
- Redis cache configuration options
