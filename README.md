# Build the Docker image
docker build -t milestone-admin .

# Run the container
docker run -p 3001:80 milestone-admin
