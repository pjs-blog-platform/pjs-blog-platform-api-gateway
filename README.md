# PJS Blog Platform API Gateway

Welcome to the PJS Blog Platform API Gateway! This is the API Gateway for the PJS Blog Platform, built using .NET 8. The API Gateway serves as the single entry point for all client requests, routing them to the appropriate microservices.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Development](#development)
- [License](#license)
- [Contact](#contact)

## Introduction

The PJS Blog Platform API Gateway is designed to manage and route requests from the frontend to the appropriate backend microservices. It handles cross-cutting concerns such as authentication, logging, and request aggregation, ensuring a streamlined and secure communication layer.

## Features

- **Request Routing**: Routes incoming requests to the correct microservice.
- **Authentication**: Manages authentication and authorization across services.
- **Load Balancing**: Distributes requests evenly across service instances.
- **Logging and Monitoring**: Provides centralized logging and monitoring of all requests.
- **API Aggregation**: Combines responses from multiple services into a single response.
- **Rate Limiting**: Controls the rate of incoming requests to prevent abuse.

## Architecture

The API Gateway sits between the client application and the microservices. It handles:

- **Routing**: Directs requests to the correct microservice.
- **Authentication**: Verifies tokens and user credentials.
- **Logging**: Captures and stores logs of incoming requests and outgoing responses.
- **Aggregation**: Combines data from multiple services when needed.

## Installation

To get started with the API Gateway, clone the repository and restore the dependencies:

```bash
git clone https://github.com/pjs-blog-platform/pjs-blog-platform-api-gateway.git
cd pjs-blog-platform-api-gateway
dotnet restore
```

## Development
To start the API Gateway, run:
```bash
dotnet run
```

To build the application for production, use:
```bash
dotnet publish -c Release
```

This will create an optimized production build in the bin/Release/net8.0/publish directory.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

For any inquiries, feedback, or support, please contact us at:

- **Email**: pjorge.silvaa@gmail.com
- **Phone Number**: +351 913 955 007
