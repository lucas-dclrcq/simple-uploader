# Simple Uploader

This is a simple file uploader application using Docker, NGINX, and a basic HTML file. The objective of this project is
to provide a minimal and efficient file upload solution that is easy to deploy and use.

## Features

- **File Upload**: A simple HTML interface for uploading files.
- **NGINX**: Serves the frontend and handles file storage.
- **Dockerized**: Easy to set up and run using Docker.

## Prerequisites

- [Docker](https://www.docker.com/) installed on your system.
- Basic understanding of Docker and NGINX.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/simple-uploader.git
   cd simple-uploader
   ```

2. Build the Docker image:

   ```bash
   docker build -t simple-uploader .
   ```

3. Run the container:

   ```bash
   docker run -d -p 8080:80 --name uploader simple-uploader
   ```

4. Access the application:

   Open your web browser and navigate to `http://localhost:8080`.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Happy uploading! 🎉