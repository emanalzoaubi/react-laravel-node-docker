# Docker Compose - React, Laravel, MySQL, PhpMyAdmin, Node.js

Just a basic boilerplate to start directly coding on React, Node.js, Laravel, MySQL and PhpMyAdmin with Docker Compose.

## Technologies Used

### Frontend

- NodeJS 16.14.0 Alpine3.14
- React 18.2.0

### Backend

- Laravel 9
- Composer 2.5.5
- NodeJS 16.14.0 Alpine3.14

### MySQL and PhpMyAdmin

MySQL Version: 8.0.x

##Getting Started
###Prerequisites

- Docker
- Docker Compose

## Installation

Clone the repository:

`git clone https://github.com/your-username/your-repo.git`

Navigate to the project directory:

`cd your-repo`

Build and run the containers:

`docker-compose up --build`

Open a web browser and you can access

- React: http://localhost:3000
- Laravel application http://localhost:8000
- NodeJs: http://localhost:3001
- PhpMyAdmin: http://localhost:8080 and log in with the default credentials username: root, password: password.

### Using the Project

### Troubleshooting

You may encounter issues while running the project on Windows, you can follow these steps:

- Install WSL2 https://learn.microsoft.com/en-us/windows/wsl/install
- Install Ubuntu for Windows https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview
- After install Ubuntu on your machine, set WSL version to Ubuntu-20.04 using
  `wsl --set-version Ubuntu-20.04 2`

- Install Docker Desktop https://docs.docker.com/desktop/install/windows-install/

- Open Docker Desktop, go to settings, Resources, WSL Integration and then enable integration with additional distros: Ubuntu-20.04
- Open File Explorer and go to Linux, Ubuntu-20.04, home, your username and put your code inside it then open it using VS code.
- In VS Code, open Ubuntu-20.04 (WSL) terminal and run the following commands to build and run docker composer.
  `docker-compose up --build`
