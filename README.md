## QuickPic - Tools For Pictures (By Theo)

I wanted a better way to upscale svgs as pngs so I built it. Also wanted a better way to make images into squares. Open source because why not. Free because it only runs on client.

## Building and Running with Docker

To build and run the application using Docker and Docker Compose, follow these steps:

1. **Ensure Docker and Docker Compose are installed** on your machine. You can download them from [Docker's official website](https://www.docker.com/products/docker-desktop).

2. **Build the Docker image**:
   ```bash
   docker-compose build
   ```

3. **Run the Docker container**:
   ```bash
   docker-compose up
   ```

4. **Access the application**:
   - Open your web browser and go to `http://localhost:3000` to view the application.

5. **Stopping the application**:
   - To stop the application, press `Ctrl+C` in the terminal where Docker Compose is running.
   - Alternatively, you can run:
     ```bash
     docker-compose down
     ```

These steps will help you get the application up and running in a Docker container using Docker Compose.
