# 𝐓𝐡𝐞 𝐏𝐫𝐢𝐧𝐜𝐢𝐩𝐥𝐞𝐬 𝐎𝐟 𝐍𝐞𝐭𝐰𝐨𝐫𝐤𝐢𝐧𝐠 𝐈𝐧 𝐃𝐨𝐜𝐤𝐞𝐫 🤔🚀🐳

![image](https://github.com/user-attachments/assets/3481e583-a368-42bb-9bd7-d93da8cc95ed)

- In Docker, containers need to be able to communicate with one another efficiently and securely which means that
- networking is such an important aspect that keeps Docker and containers going!
- understanding basic networking concepts in Docker is essential for managing containerised applications effectively

 So Lets cover some networking concepts in Docker and understand how they work!!

 ## 1. Bridge Networking

 ![image](https://github.com/user-attachments/assets/ddd898b0-90f5-464d-b4d1-dcd51fae115f)

 - A Bridge network is a default network mode for containers on the same machine 
 - Containers connected to the Bridge Network can communicate with eachother using their own IP addresses
 - its isolated from your host machines network which provides and extra layer of security.

## 2. Host Networking 

![image](https://github.com/user-attachments/assets/a1e206ce-c6ec-4c1a-8fa5-162f134a7293)

- In host networking, a container uses the hosts machines network directly without any isolation
- Its as if the container is plugged directly into your home network with no distinction between the container and the host
- This mode is useful for applicationsthat need to closely interact with the host system.

## 3. None Networking 

![image](https://github.com/user-attachments/assets/d3fe0e58-2d6f-4dbe-ac8e-0580c6e45c1e)

- This type of networking gives a container no network interface at all which makes it completely isolated
- None networking is used so that a container has no network access whatsover
- This is useful for certain security scenarios

## Why is Docker Networking important in DevOps? 🤔♾️

- Docker networking in DevOps is particularly important because it simplifies the implementation of microservices architecture
- Microservices allow different parts of an application to run as independent services each in its own container.
- Docker networking ensures that these services can communicate with eachother efficiently and securely
- Dockers networking model is highly scalable, meaning that you can easily connect and scale services as your apllication grows 
