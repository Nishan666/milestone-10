# Build the Docker image
docker build -t milestone-admin .

# Run the container
docker run -d --name milestone-admin --restart unless-stopped -p 3001:80 milestone-admin
