# Project Setup Guide

## Overview
This project is designed to provide an earth sync solution that combines various tools and technologies to achieve a unified environmental data management.

## Technology Stack
- **Programming Language:** Python 3.x
- **Framework:** Django 3.x
- **Database:** PostgreSQL
- **Frontend:** React.js
- **Containerization:** Docker

## Prerequisites
Before you start, ensure you have the following tools installed:
- Python 3.x
- Docker
- Git
- PostgreSQL

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/weidig8/earthsync.git
   cd earthsync
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up the database:
   - Create a PostgreSQL database.
   - Update your database connection settings in the `settings.py` file.

## Running the Project
To run the project locally:
1. Start the Docker containers:
   ```bash
   docker-compose up
   ```
2. Navigate to `http://localhost:8000` to access the app.

## Environment Variables
Make sure to create a `.env` file in the root directory and include the following variables:
- `DATABASE_URL`
- `SECRET_KEY`
- `DEBUG` (set to `True` for development)

## Development Workflow
1. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
2. Implement changes and commit them:
   ```bash
   git add .
   git commit -m "Add your commit message"
   ```
3. Push the branch and create a pull request:
   ```bash
   git push origin feature/your-feature-name
   ```

## Planned Features
- Integration of real-time data syncing.
- User authentication and authorization.
- Dashboard for data visualization.

## Contribution Guidelines
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new feature branch.
3. Ensure your code follows the style guidelines.
4. Submit a pull request outlining your changes.

Thank you for checking out this project! If you have any questions, feel free to reach out.