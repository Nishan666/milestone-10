# Build the Docker image
docker build -t my-vite-app .

# Run the container
docker run -p 8080:80 my-vite-app
