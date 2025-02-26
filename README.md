# Job Board Platform

## Overview
This project is a job board platform designed to help job seekers find employment opportunities. The backend is built with Python (Django) and is being enhanced with Java Spring Boot. We use a variety of tools and technologies to ensure the platform is efficient, secure, and scalable.

## Tech Stack
- **Backend:** Python (Django), Java (Spring Boot)
- **Database:** PostgreSQL
- **Caching:** Redis
- **Cloud:** AWS
- **Authentication:** OAuth2/JWT
- **CI/CD:** Docker, GitHub Actions

## Features
- Job Posting API: Optimized endpoints for posting jobs.
- Improved Authentication: Enhanced JWT implementation with refresh tokens.
- Email Verification: SendGrid integration for email verification and notifications.
- Search Functionality: Optimized search algorithms and database queries.
- Redis Caching: Caching frequently accessed data for better performance.

## Setup Instructions
1. **Clone the Repository:**
   
   ```bash
   git clone <repository_url>
   ```

2. **Set Up Environment:**

- Use Docker to set up the development environment
- Create a Docker Compose file to orchestrate containers for Django, PostgreSQL, Redis, and other services

3. **Install Dependencies:**

    ```bash
    cd <project_directory>
    pip install -r requirements.txt
    ```

4. **Run the Application**
    ```bash
    docker-compose up
    ```

## CI/CD Pipeline

- We use GitHub Actions for Ci/CD.
- The pipeline includes testing, linting, and deployment stages

## Contribution Guidelines

- Fork the repository and create a new branch for your feature or bug fix
- Submit pull requests with detailed descriptions of your changes
- Ensure your code passes all tests and meets code quality standards

## License

This project is licensed under the MIT License. See the LICENSE file for more details.