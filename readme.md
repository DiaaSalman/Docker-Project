#AliDarwish 
#Omnifood - Frontend Project
PREREQUISITES:
Make sure you have Git and Docker installed on your machine.
To verify, run these in the terminal:
git --version
docker --version
-----------------------------------------------------------
STEP 1: Clone the project from GitHub
git clone https://github.com/DiaaSalman/Docker-Project
cd omnifood-frontend
-----------------------------------------------------------
STEP 2: Build the Docker image
docker build -t omnifood-frontend
-----------------------------------------------------------

# Omnifood - Frontend Project (Dockerized) by DataSense
# Omnifood - Frontend Project (Dockerized) by DataSense
## How to run


```bash
docker build -t omnifood-frontend .
docker run -d -p 8080:80 omnifood-frontend

## Useful Additional Docker Commands

- To see all running containers:

```bash
docker ps
