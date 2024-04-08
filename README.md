 Images or Containers Taking Up Too Much Space?
 I encountered an issue when i run docker conatiner My system is running out of disk space due to Docker images, containers, or volumes that are no longer needed. 
 I used docker image prune -a to remove unused Docker images.
 Remove stopped containers, unused networks, and build cache: -- docker system prune
 Remove unused volumes (Caution: Make sure you don’t delete important data):- docker volume prune
