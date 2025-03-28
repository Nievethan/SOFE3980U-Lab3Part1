﻿# SOFE3980U-Lab3Part1

Video Demonstration:
Deployment Methods Video: https://youtu.be/WtUPrpcbWfQ
Maven App Deployment Video: https://youtu.be/ubYN4CEpd68

Deliverables:
1. Briefly summarize what you have learned about docker and Kubernetes, including their terminologies and descriptions.
Docker is a platform that automates the deployment of applications inside containers. These containers come with the application and all the required dependencies to run the application.
Kubernetes are a container orchestration platform developed by Google. It automates the deployment, scaling, and management of containerized applications.


2. What are the advantages and disadvantages of using docker images?
Advantages:
Portability: Ensures applications run consistently across different environments.
Efficiency: Shares the host OS kernel, reducing resource consumption compared to traditional virtual machines.
Scalability: Facilitates easy scaling of applications by deploying multiple container instances.


Disadvantages:
Security Concerns: Containers share the host OS kernel, which can pose security risks if not managed properly.
Networking Complexity: Managing container networking, especially in large-scale deployments, can be intricate.
