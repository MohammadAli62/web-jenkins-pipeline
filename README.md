Deploying a Web Application Using Docker and Kubernetes on an AWS Instance: A Step-by-Step Guide
Introduction:

Inthis tutorial, we will walk through the process of deploying a simple HTML web application using Docker and Kubernetes on an AWS EC2 instance. Docker allows us to containerize our application, while Kubernetes provides orchestration and management of containers. By leveraging these technologies, we can easily deploy and manage our web application in a scalable and efficient manner on AWS.

Prerequisites:

An AWS account with appropriate permissions to create EC2 instances and manage Kubernetes clusters.
Basic understanding of Docker and Kubernetes concepts.
Git installed on your local machine.
Step 1:

Clone the HTML Code Repository: First, clone the HTML code repository from GitHub. This repository contains the HTML files for our web application.
To get started, the first step is to clone the Git repository. You can do this by running the following command in your terminal:

https://github.com/MohammadAli62/web-jenkins-pipeline.git

Step 2:

Build Docker Image: Build the Docker image using the following command:

Copy code

docker build -t ali889/my-webiste:02 .


Step 4:

Run Docker Container Locally (Optional): You can run the Docker container locally to test your web application before deploying it to Kubernetes.

docker run -d -p 80:80 ali889/my-webiste:02

Step:4

To deploy your website to your AWS instance with the IP address 13.208.128.114:80, you can run the necessary commands. Assuming you have configured your AWS environment and have your website files ready.
