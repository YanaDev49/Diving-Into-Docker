# Here Are All The Essential Docker Commands That You Need To Know! 📈♾️

![image](https://github.com/user-attachments/assets/20d2a331-b125-4f40-9433-c060a23130b1)

#### These Commands will keep your docker enviroments clean organised and running smoothly as you start working with more containers in your projects!

## Command 1:⤵️

![image](https://github.com/user-attachments/assets/c9b0f974-cf4a-44a5-8095-16c843d9617d)

- This docker command lists all the Docker images that are stored locally on your system. Each image listed provides important information about the image
  Like the repository name, ID, when it was created and the size. This is useful for keeping track of which images are available and identifying any that you want to clean up. 

## Command 2:⤵️

![image](https://github.com/user-attachments/assets/1b054b05-31ab-48a9-a845-864f4a8bd524)

- when you need more details about a specific docker image, you can run the ' docker inspect ' command followed by the ID of the
  container you wish to view the details of. you can get the ID of the docker image from the previous command that we ran ' docker images '.

## command 3:⤵️

![image](https://github.com/user-attachments/assets/c8e5c137-0382-404f-9351-496d6bfe6b07)

- docker rmi is used to remove images that you no longer need
- To remove docker images, all you need to do is run 'docker rmi ' followed by the image ID
- Its important to note that if the image is still being used by a container, docker will not remove it and you may need to stop the container from running first.

## Command 4:⤵️

![image](https://github.com/user-attachments/assets/de4ff99a-6eec-4d01-828d-b6272fb4c9af)

- Instead of removing images 1 by 1, docker provides a command that cleans up all unused images, containers, networks and volumes in one go
- This is useful for clearing resources that are no longer needed

- 
