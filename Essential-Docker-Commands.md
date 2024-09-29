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

## Command 5:⤵️

![image](https://github.com/user-attachments/assets/f4147d0d-f6ee-4eef-aaab-44c4fbd2b094)

- To see which containers are correctly running on your system, you can run the ' docker ps ' command.

## Command 6:⤵️

![image](https://github.com/user-attachments/assets/3f0302a8-a70c-46aa-8704-2cd7ec4c02c7)

- To stop a container from running run the ' docker stop ' command followed by the image ID of the container you want to stop
- However once a container has been stopped, it still exists on your system in a stopped state

## Command 7:⤵️

![image](https://github.com/user-attachments/assets/61e4f44f-67ca-44ed-b4d6-39007bec1f72)

- To completely remove it, you can run the ' docker rm ' command followed by the container ID of your choice


### By managing images and containers effectively, you ensure that your system stays organised and efficient. These commands are apart of your day to day work flow for anyone working with docker.

![ThereYouHaveItSheaWhitneyGIF (2)](https://github.com/user-attachments/assets/267de80e-7479-416a-857f-3e5c6668651e)
