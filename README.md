# Real-Time Vote Streaming Application

This project demonstrates a real-time vote streaming application using Docker, PostgreSQL, Python, Apache Kafka, Apache Spark for transformations, and Streamlit for visualizations.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Real-Time Vote Streaming Application is designed to showcase a scalable and efficient system for processing and visualizing voting data in real-time. It utilizes various technologies to achieve this, including Docker for containerization, PostgreSQL for data storage, Apache Kafka for message streaming, Apache Spark for data transformations, and Streamlit for interactive visualizations.

## Features

- Real-time vote streaming and processing.
- Scalable architecture using Docker containers.
- PostgreSQL database for persistent storage of vote data.
- Apache Kafka for efficient message streaming.
- Apache Spark for data transformations and analytics.
- Interactive visualizations powered by Streamlit.

## Prerequisites

Before you begin, ensure you have the following installed:

- Docker
- Docker Compose
- Python 3.9 and up
- Apache Kafka
- Apache Spark
- PostgreSQL

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/real-time-vote-streaming.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Real-Time-Vote-Application
    ```

3. Build and start the Docker containers:

    ```bash
    docker-compose up --build docker.yml
    ```

4. Install Python dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start Apache Kafka broker and Zookeeper services.
2. Run the Spark streaming application to process incoming vote data from an API and save it in postgres and also produces those voters in producers to store it in topics.
3. Start the Streamlit server for visualizations.
4. Interact with the Streamlit dashboard to view real-time voting statistics.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.
