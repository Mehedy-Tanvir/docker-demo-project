# Build the Docker image

docker build -t docker-demo-project .

# Login to Docker Hub

docker login

# List Docker images

docker images

# Tag the image

docker tag [image-id] docker-demo-project

# Push the image to Docker Hub

docker push mehedytanvir/docker-demo-project

# Pull the image from Docker Hub

docker pull mehedytanvir/docker-demo-project

# Run the Docker image

docker run docker-demo-project
