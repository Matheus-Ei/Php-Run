# PHP Run

A simple PHP development environment using Docker.

## Getting Started

Follow these steps to get the project up and running.

### Prerequisites

Ensure you have Docker and Docker Compose installed on your machine.

  * [Docker](https://docs.docker.com/get-docker/)
  * [Docker Compose](https://docs.docker.com/compose/install/)

### Installation

1.  Clone the repository:
    ```sh
    git clone https://github.com/matheus-ei/php-run.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd php-run
    ```
3.  Start the Docker containers:
    ```sh
    docker-compose up -d
    ```
    The web server will now be running and accessible at [http://localhost:8080](http://localhost:8080).

## Usage

  * **Development:** You can add your PHP files to the root directory. The `index.php` file is the entry point for your application. The content of the current directory is mounted to the `/var/www/html` volume in the container.
  * **Stopping the environment:** To stop the containers, run the following command:
    ```sh
    docker-compose down
    ```
