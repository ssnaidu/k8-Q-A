# k8-Q-A
Q. What is docker registry?
A. Place where docker images are stored

Q. What is docker image?
A. Docker image is a template which contains Data, OS, and Softwares

Q. What is docker container?
A. Docker container is copy of dokcer image which has resoucersces like CPU, MEM, Network and storage

Q. How to build docker image?
A. Using Dockerfile

Q. Explain dokcer image naming Convention 
A. madhuchary/dockerdemo:v1 
    madhuchary is docker account name
    dockerdemo is image name
    v1 is tag

Q. How to expose ports in docker?
A. Using -p or -P
    -p you need to specify port
    -P dynamic port

Q. How to ssh into docker container
A. docker exec -it cntid /bin/bash
