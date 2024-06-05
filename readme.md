# StreamYard Clone

A simple StreamYard clone built using Docker and Socket.IO.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Real-time video and audio streaming
- Chat functionality
- Multiple user support
- Easy to deploy using Docker

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Docker installed on your computer
- Docker Compose installed (if not included with Docker)
- Basic knowledge of Docker and Socket.IO

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/streamyard-clone.git
    cd streamyard-clone
    ```

2. **Build and run the Docker containers:**

    ```sh
    docker-compose up --build
    ```

## Usage

1. **Access the application:**

    Open your web browser and navigate to `http://localhost:3000`.

2. **Start streaming:**

    - Click on the "Start Stream" button to begin streaming.
    - Allow camera and microphone access when prompted.
    - Share the link with others to join your stream.

## Folder Structure

```plaintext
streamyard-clone/
├── backend/
│   ├── Dockerfile
│   ├── package.json
│   ├── server.js
├── frontend/
│   ├── Dockerfile
│   ├── package.json
│   ├── public/
│   ├── src/
├── docker-compose.yml
└── README.md

# Contributing to StreamYard Clone

We welcome contributions to StreamYard Clone! Follow the steps below to get started.

## How to Contribute

1. **Fork the repository:**

    - Navigate to the [StreamYard Clone repository](https://github.com/yourusername/streamyard-clone).
    - Click the "Fork" button in the top right corner.

2. **Create a new branch:**

    - Open your terminal or command prompt.
    - Clone your forked repository to your local machine:
        ```sh
        git clone https://github.com/yourusername/streamyard-clone.git
        ```
    - Navigate to the cloned repository:
        ```sh
        cd streamyard-clone
        ```
    - Create a new branch for your feature or bug fix:
        ```sh
        git checkout -b feature-branch
        ```

3. **Make your changes:**

    - Implement your feature, bug fix, or improvement.
    - Ensure your code follows the project's style guides and passes all tests.

4. **Commit your changes:**

    - Stage your changes:
        ```sh
        git add .
        ```
    - Commit your changes with a meaningful message:
        ```sh
        git commit -m 'Add some feature'
        ```

5. **Push to the branch:**

    - Push your changes to your forked repository:
        ```sh
        git push origin feature-branch
        ```

6. **Open a Pull Request:**

    - Go to your forked repository on GitHub.
    - Click on the "Compare & pull request" button next to your feature branch.
    - Fill in the required information and create the pull request.

## Additional Guidelines

- **Sync with Upstream:** Before making any changes, sync your fork with the upstream repository to avoid merge conflicts:
    ```sh
    git checkout main
    git pull upstream main
    git checkout feature-branch
    git rebase main
    ```
- **Describe Your Changes:** When opening a pull request, provide a clear description of what your changes do and why they are necessary.
- **Link Issues:** If your changes address an issue, link it in the pull request description using the format `Closes #issue-number`.
- **Review Process:** Be responsive to feedback during the review process. Make any requested changes and update your pull request.

Thank you for contributing to StreamYard Clone!

If you have any questions, feel free to ask in the [issues](https://github.com/AdityaSahu786/StreamYard_Clone/issues) or reach out to the maintainers.
