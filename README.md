#### Nginx Dockerfile


###  Download [automated build](https://registry.hub.docker.com/u/dockerfile/nginx/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull nginx`

   (alternatively, you can build an image from Dockerfile: `docker build -t nginx github.com/nginx`)


### Build the image

    docker build -t nginx

### Run the contenair

    docker run -p 80:80 nginx

