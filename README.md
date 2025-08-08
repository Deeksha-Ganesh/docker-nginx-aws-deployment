Streamlined Web Application Deployment using Docker in AWS with Nginx

## Project Overview
This project demonstrates how to create, containerize, and deploy a simple static web application using Docker and Nginx on an AWS EC2 instance.  
It follows a streamlined approach - from writing the project files to deploying them live on a cloud server.


## Tools & Technologies
- AWS EC2 (Ubuntu 22.04 LTS)
- Docker Engine
- Nginx Web Server
- HTML, CSS, JavaScript



## Project Steps
1. Launch and AWS EC2 Instance
2. Create the Web Application
3. Create files:
    index.html – Main webpage
    styles.css – Styling
    script.js – JavaScript functionality
4. Install Docker on EC2
5. Write the Dockerfile
7. Build the Docker Image
    docker build -t webapp-demo
9. Run the Container
     docker run -d -p 80:80 webapp-demo

## Result
Access it in a browser.

<img width="1433" height="701" alt="image" src="https://github.com/user-attachments/assets/794bab72-e8ad-453d-a426-ebbfa37bd30c" />

