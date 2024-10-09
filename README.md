## Docker command
```
1. docker images
To list all the Docker images present in the Docker server.

2. docker image inspect [image-id]
To display detailed image information for a given image ID.

3. docker image rm [image-id]
To remove one or more images for a given image ID.

4. docker build . -t [image-name]
To generate a Docker image based on a Dockerfile.

5. docker run -p [hostport]:[containerport] [image_name]
To start a Docker container based on a given image.

6. docker ps
To show all running containers.

7. docker ps -a
To show all containers including running and stopped.

8. docker container start [container-id]
To start one or more stopped containers.

9. docker container pause [container-id]
To pause all processes within one or more containers.

10. docker container unpause [container-id]
To resume/unpause all processes within one or more containers.

11. docker container stop [container-id]
To stop one or more running containers.

12. docker container kill [container-id]
To kill one or more running containers instantly.

13. docker container restart [container-id]
To restart one or more containers.

14. docker container inspect [container-id]
To inspect all the details for a given container ID.

15. docker container logs [container-id]
To fetch the logs of a given container ID.

16. docker container logs -f [container-id]
To follow the log output of a given container ID.

17. docker rm [container-id]
To remove one or more containers based on container IDs.

18. docker container prune
To remove all stopped containers.

19. docker image push [container_registry/username:tag]
To push an image from a container registry.

20. docker image pull [container_registry/username:tag]
To pull an image from a container registry.

21. docker image prune
To remove all unused images.

22. docker container stats
To show all container statistics like CPU, memory, I/O usage.

23. docker system prune
Remove stopped containers, dangling images, and unused networks, volumes, and cache.

24. docker rmi [image-id]
To remove one or more images based on image IDs.

25. docker login -u [username]
To log in to Docker Hub container registry.

26. docker logout
To log out from Docker Hub container registry.

27. docker history [image-name]
Displays the intermediate layers and commands that were executed when building the image.

28. docker exec -it [container-id] sh
To open a shell inside a running container and execute commands.

29. docker compose up
To create and start containers based on a given Docker Compose file.

30. docker compose down
To stop and remove containers for services defined in the Compose file.
```
