# GitLab in Docker

This project provides a streamlined approach to deploying GitLab within a Docker environment, facilitating efficient source code management and continuous integration/continuous deployment (CI/CD) pipelines.

## Features

- **Easy Deployment**: Quickly set up GitLab using Docker Compose.
- **Data Persistence**: Ensures that GitLab data remains intact across container restarts.
- **Customizable Configuration**: Modify GitLab settings through environment variables.

## Prerequisites

- [Docker](https://www.docker.com/get-started) (version 20.10 or higher)
- [Docker Compose](https://docs.docker.com/compose/install/) (version 1.29 or higher)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/DoThanhLong15/Gitlab_In_Docker.git
   ```

2. **Navigate to the Project Directory**:
  ```bash
  cd Gitlab_In_Docker
  ```

3. **Start the GitLab Service**:
  ```bash
  docker-compose up -d
  ```

4. **Access GitLab**:
   - Once the service is running, navigate to http://localhost:8000 in your web browser.
