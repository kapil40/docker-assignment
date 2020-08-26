# docker-assignment
![image](https://user-images.githubusercontent.com/62129584/91305800-39a85f80-e7c9-11ea-89a0-bb133d936876.png)

To push image into private registry:

1. Login using docker login
2. Assign tag to the image by using the command:
    docker tag tag_name image_name
3. Push it into registry by using:
     docker push image_name/tag
