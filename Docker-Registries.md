# What are Docker Registries 🤔

![image](https://github.com/user-attachments/assets/b1b6e36f-568e-4487-a3d3-ff5c8b490821)

- Docker Registries are important for managing, storing and deploying docker images especially when working in a DevOps enviroment
- Docker Registries are storage and distribution hubs for your docker images
- A Registry is where your docker images live when they are not running as containers, it makes your containers accessoble whenever you need them!

 ## Key Features Of Docker Registries

### 1. Public Registries
![image](https://github.com/user-attachments/assets/7447ccd6-3c87-4902-bf25-34dcd0319b3c)

- Docker Hub is an example of a public Docker Registry which is open to everyone!
- Its a platform where you can share your images to the world or use community provided images as the foundation for your applications.

### 2. Private registries (AWS-ECR)
![image](https://github.com/user-attachments/assets/4cb2954c-727f-4de4-9faf-8c0b36f447e4)

- These docker registries are restricted which means that only you have access these docker images
- They allow you to control who has access to your images, so you can make it public or private
- This is important when handling sensitive applications where you dont want to anyone to access these images

## Why are Docker Registries so important in the DevOps enviroment? 🤔
![image](https://github.com/user-attachments/assets/224bed46-3af9-480e-81ee-bbc690044ff2)

- Docker Registries streamline the deployment process which means that once your docker images are strored within the registry, they can be easily be accessed and deployed accross multiple enviroments
  
- This makes it much faster and more relaible to put out new features and updates
  
- Docker registries enhance collaboration within a team because when images are stored in a centralized registry, everyone on your team has access to the same resources which makes it easier to share and manage images, improving overall teamwork and efficiency
  
-  A Docker Registry ensures that everyone is on the same page
  
-  Lastly Docker Registries ensure consistency accross different enviroments, so by storing your images in a registry, you can be sure that the exact same image is being used in development, testing and production

## How do Registries fit in the overall workflow? 🤔
![image](https://github.com/user-attachments/assets/0a7adb38-81bd-42e8-b2f9-f44c17c10e48)

### In A DevOps workflow, Docker Registries are used to build!

- So when you build your docker image locally, creating a docker file and built the image, before pushing the image to a registru you test it to ensure everything is working as expected by creating a container out of it
  
- Once the image is ready and the apllication runs as expected, then you push the image to AWS ECR
  
- lastly you pull that image from the registry to deploy it to your production or staging enviroment. This is where pipelines come in where you are pulling the images that youve built directly from this registry.

- once youve pushed this image to the registry you are now pulling the image within your pipeline so that you can do this automatically 

### This workflow ensures that the same image is deployed accross all enviroments which reduces the risk of inconsistencies and errors!!

![ThereYouHaveItSheaWhitneyGIF](https://github.com/user-attachments/assets/6407fcee-c107-4498-a063-7d6af5da5dd1)





