#### Docker Commands 

1->Docker verserion  -->docker --version 
2->Running containers -->docker ps
3->All running containers-->docker ps -a
3->images -->docker images
4->delete or remove image  ->docker rmi <image_name>
5->pull an image -> docker pull <image_name>
6->Search an image on dockerHub->docker search <image_name>
7->run a container->docker run --name <container_name> -d -p p1:p2 <image_name>
8->  stop a running container ->docker stop<container_name>
9->remove  a stopped container->docker rm <container_name> 
10->Runs a command inside an existing container -->docker exec -it <container_name_or_id> <command>

11->Displays the logs of a specific container -->docker logs <container_name >

12->Build an image from a dockerfile docker build docker build -t <image_name> <path_to_dockerfile_directory>

13->  Push an Image to Docker Hub -->docker push <dockerhub_username>/<image_name>


