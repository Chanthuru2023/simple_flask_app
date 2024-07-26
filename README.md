# Simple Flask App

This is a simple Flask application used as an example for setting up and running a Flask app.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Running the App](#running-the-app)
- [Testing](#testing)
- [Docker](#docker)
- [CI/CD with Jenkins](#cicd-with-jenkins)
- [Monitoring with AWS CloudWatch](#monitoring-with-aws-cloudwatch)
- [License](#license)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Chanthuru2023/simple_flask_app.git
    cd simple_flask_app
    ```

2. **Create a virtual environment and activate it**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

The application can be used to demonstrate a basic Flask setup.

## Running the App

1. **Start the Flask app**:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://localhost:5000` to see the app running.

## Testing

1. **Run the tests using Pytest**:
    ```bash
    pytest tests/
    ```

## Docker

1. **Build the Docker image**:
    ```bash
    docker build -t simple-flask-app .
    ```

2. **Run the Docker container**:
    ```bash
    docker run -p 5000:5000 simple-flask-app
    ```

## CI/CD with Jenkins

1. **Jenkinsfile** is included to automate the build and deployment process using Jenkins.

2. Configure Jenkins to use the provided `Jenkinsfile`.

## Monitoring with AWS CloudWatch

1. The configuration for CloudWatch is provided in the `config.json` file.

2. Install and configure the CloudWatch agent to monitor the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
