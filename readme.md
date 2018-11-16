# VGG Image Annotator (VIA) docker file

## steps build the docker file

1. clone the repository 
2. `docker build -t via-2.0.2:v1 -f via.dockerfile .`
3. `docker run -d -p 93:80 via-2.0.2:v1`
4. Browse `http://localhost:93`
