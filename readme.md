# Microservices Project

This project implements a microservices architecture using Node.js. It includes several independent services that communicate with each other to provide a complete application.

## Services

*   **API Gateway:**  Handles incoming requests and routes them to the appropriate service.
*   **Identity Service:** Manages user authentication and authorization.
*   **Media Service:**  Handles media uploads, processing, and storage.
*   **Post Service:** Manages the creation, retrieval, and storage of posts.
*   **Search Service:** Provides search functionality across all services.

## Technologies Used

*   Node.js
*   Express.js
*   Docker
*   Docker Compose
*   RabbitMQ (for inter-service communication)

## Getting Started

1.  **Prerequisites:**
    *   Docker and Docker Compose installed.

2.  **Clone the repository:**
    ```shell
    git clone <repository-url>
    cd microservices
    ```

3.  **Start the services:**
    ```shell
    docker-compose up --build
    ```

## Configuration

See the individual service directories for specific configuration options.
