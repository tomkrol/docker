**1. Build an image from Dockerfile**

    docker build -t centos_test .
    
**2. Run container on the image in interactive mode**

    docker run --name test -it centos_test
