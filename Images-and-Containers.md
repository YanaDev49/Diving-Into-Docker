# What Are Images And Containers In Docker? 🐳

![image](https://github.com/user-attachments/assets/cc8f9bd0-4d16-498e-a375-885fe2f2fcd9)

- Images are known as templates for creating containers. We can think og it as a snapshot
of an application at a certain point in time (kind of like a git commit hehe 😄)

- One important point to understand is that images are 𝒊𝒎𝒎𝒖𝒕𝒂𝒃𝒍𝒆
- This means that they dont change once they are created unless you recreate the whole image.
- The immutibility ensures that the application runs consistently, no matter where its deployed.
 
    ![image](https://github.com/user-attachments/assets/f243f977-7a06-4e4e-8807-f689fba70fe9)

- Containers on the otherhand are running instances of images, which are snapshots of an application.
- Contains are what actually runs your application. you can manipulate it, start, stop and modify them as needed!

# How Do We Create Docker Images 🐳🚀

![image](https://github.com/user-attachments/assets/c5c7c2ce-4c04-4c8c-9a0e-94d92113553f)

- We use something called a docker file to build docker images, which contains all the instructions you need to set up the process

## This is what a Docker File looks like!!
![image](https://github.com/user-attachments/assets/4a4df66e-cc59-4fc3-b057-152deaba361c)

This is an image of a small docker file i have created for a little python script i made! 

![image](https://github.com/user-attachments/assets/e74b94a1-97e2-4d03-a8f0-aa96123a1090)

This is just a minor python script that prints text on the screen, but ill show you how i developed a more detailed script and containerised it using docker in upcoming files! 😆

## And There You Have it!! We have looked at the details of both images and containers in docker!!🚀🚀

![ThereYouHaveItSheaWhitneyGIF](https://github.com/user-attachments/assets/247eca35-7759-46ac-a8ec-20dd1af68a71)
