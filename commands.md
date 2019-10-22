**1. Build an image from Dockerfile**

    docker build -t centos_test .
    
**2. Run container on the image in interactive mode**

    docker run --name test -it centos_test
    
**3. Start existing docker**
   
    docker test start
    
**4. Get to bash of running container**
       
    docker  exec -it test bash
    
**5. Pushing docker image to Hub**

    docker tag drill:v2 docker.com/drill:v2
    docker push docker.com/drill:v2
