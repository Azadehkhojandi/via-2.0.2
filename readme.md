# VGG Image Annotator (VIA) docker file

## Steps to build the docker file

1. clone the repository 
2. `docker build -t via-2.0.2:v1 -f via.dockerfile .`
3. `docker run -d -p 93:80 via-2.0.2:v1`
4. open browser and browse `http://localhost:93`

## Steps to run from docker hub

1. `docker pull azadehkhojandi/via-2.0.2`
2. `docker run -d -p 99:80 azadehkhojandi/via-2.0.2`
3. open browser and browse `http://localhost:99/`
