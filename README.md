
markdown
Copy code
# Docker Compose Setup for TheHive with OpenCTI

This repository contains a Docker Compose configuration file (`docker-compose.yml`) for setting up TheHive with OpenCTI. TheHive is a scalable, open-source, and free Security Incident Response Platform designed to make life easier for SOCs, CSIRTs, and CERTs. OpenCTI is an open-source Cyber Threat Intelligence platform that focuses on knowledge management.

## Prerequisites

Before running the Docker Compose setup, ensure that you have Docker and Docker Compose installed on your system.

## Usage

1. Clone this repository to your local machine.
2. Navigate to the directory containing the `docker-compose.yml` file.
3. Modify the environment variables in the file to match your specific configuration (passwords, etc.).
4. Run the following command to start the services:

    ```bash
    docker-compose up -d
    ```

   The `-d` flag runs the containers in detached mode, meaning they will run in the background.
