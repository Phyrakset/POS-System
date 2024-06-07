# POS-System

## Project Description
The POS-System is a comprehensive point of sale (POS) solution designed to manage sales, inventory, and customer relationships for small to medium-sized businesses. This system integrates various modules such as `api`, `db`, `file`, and `web` to provide a seamless and efficient POS experience. The backend is built with Laravel, a robust PHP framework...

## Directory Structure
- `api/`: Contains the backend API services built with Laravel for handling business logic and data processing.
- `db/`: Contains database configurations and migrations.
- `file/`: Stores file-related functionalities and assets.
- `web/`: Contains the frontend web application.
- `docker-compose.yml`: Docker Compose file to set up and run the application using Docker.
## Installation

### Prerequisites
- [Docker](https://www.docker.com/products/docker-desktop) installed on your machine.
- [Git](https://git-scm.com/downloads) installed on your machine.
- [Composer](https://getcomposer.org/) installed on your machine (for Laravel dependencies).

### Steps
1. **Clone the Repository**
   ```sh
   git clone git@github.com:Phyrakset/POS-System.git .
   ```
   
2. **Navigate to the Project Directory** 
   ```sh
   cd POS-System
   ```
3. **Install Laravel Dependencies** 
   ```sh
   composer install
   ```
4. **Copy .env Files** 
   ```sh
   cp .env.example .env
   ```
5. **Generate Application Key** 
   ```sh
   php artisan key:generate
   ```
6. **Build and Start the Application using Docker Compose** 
   ```sh
   docker-compose up --build
   ```
