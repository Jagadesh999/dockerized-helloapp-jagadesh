# Dockerized HelloApp - Jagadesh  

A simple Flask web application running inside **Docker**.  

## Features  
 Lightweight & Fast  
 Runs inside Docker  
 Simple Flask API  

## Run the App Locally  
```sh
docker run -p 5000:5000 jagadesh999/helloapp:latest
```

## Build & Push Docker Image  
```sh
# Build the Docker image
docker build -t jagadesh999/helloapp:latest .

# Login to Docker Hub
docker login

# Push the image to Docker Hub
docker push jagadesh999/helloapp:latest
```

## How to Use this Project  
1️⃣ Clone the repository:  
```sh
git clone https://github.com/jagadesh999/dockerized-helloapp-jagadesh.git
cd dockerized-helloapp-jagadesh
```

2️⃣ Run using Docker:  
```sh
docker run -p 5000:5000 jagadesh999/helloapp:latest
```

3️⃣ Open in Browser:  
👉 **http://localhost:5000**  

🌟 **If you like this project, give it a star!** 🌟

