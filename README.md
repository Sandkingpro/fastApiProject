# Build docker image

docker build -t fastapiproject:latest .

# Run docker container

docker run -d --name webapp -p 8000:8000 fastapiproject:latest