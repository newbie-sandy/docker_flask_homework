# docker_flask_homework

- Docker utilizes containerization technology to address the challenge of version discrepancies between operating systems and Python generations. It allows for the creation of isolated environments, known as containers, ensuring consistency and portability across different platforms.
- Docker Compose

- The process of Dockerizing the applications in both parts.

- The build and run commands used.

  - docker build -t (NAME of Docker Image) .   #Pull down python:3.7 alpine

  - docker images
    ![image](https://github.com/newbie-sandy/docker_flask_homework/assets/143536852/0c75eebc-0a65-4428-b2e4-a9adca324648)


  - docker run -p (LOCAL PORT): (VM port) (Name of Docker Image)
  - docker run -d -p 8080:5000 sandy   #-d for detach run container in the background??
  - docker ps   # list of running container id
  - docker stop (CONTAINER ID)
  - docker space prune -a -f   # reclaim spaces image should be stopped before deletion

- Troubleshooting
![image](https://github.com/newbie-sandy/docker_flask_homework/assets/143536852/4482f290-05cb-463b-9060-0ed74fec43f2)
![image](https://github.com/newbie-sandy/docker_flask_homework/assets/143536852/c8b2907d-8531-4255-80bf-0df3b99ebcfa)

