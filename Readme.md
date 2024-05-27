# Compose Toolkit | Docker compose

## Description
As we forget docker-compose images, sometimes its very difficult to find the exact same version with same config, so here is  Centralized Docker Compose configs for easy setup of various frameworks and tools. Contains various images

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Available Configurations](#available-configurations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Welcome to **Compose-Toolkit**! This repository provides a collection of Docker Compose configurations for various frameworks and tools. It aims to simplify the process of setting up and managing development environments.

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed on your system:
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Installation
Clone this repository to your local machine:
```bash
git clone https://github.com/swarajkumarsingh/Compose-Toolkit.git Compose-Toolkit
cd Compose-Toolkit
```

### Available Configurations
This repository includes Docker Compose configurations for:
- PostgreSQL
- Golang server
- Redis
- Temporal
- Prometheus
- Pgadmin
- Grafana
- PDF-service

### Usage
Navigate to the directory of the desired framework/tool and run Docker Compose:
```
cd <framework-directory>
docker-compose up
```
This will start the services defined in the Docker Compose file.

### Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your configurations are well-documented.

### License
This project is licensed under the MIT License. See the LICENSE file for details.