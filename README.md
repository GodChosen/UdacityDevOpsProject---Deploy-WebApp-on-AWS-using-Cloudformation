# PROJECT OWNER 
**Name:** Osazee Odigie
**Email Address:** osazee.odigie01@gmail.com

# PROJECT TITLE
**Deploy a high-availability web app using CloudFormation**

## Files Description

### networkinfrastructures.yml

This YAML template contains the code used for provisioning the AWS network infrastructures needed for the project. 

### networkinfrastructuresparameters.json

This YAML template contains the parameters used by the network infrastructures template.

### webservers.yml

This YAML template contains the code used for provisioning the cloud servers required in this project.

### webserversparameters.json

This YAML template contains the parameters used by the webservers template.

## Web Server Instance Specifications

Below are the specifications of the EC2 instances to be used to run the web application

- **Amazon Machine Image (AMI):** Ubuntu Server 18.04 LTS (HVM), SSD Volume Type - ami-003634241a8fcdec0 (64-bit x86)

- **Instance Type**: t3.medium (vCPU=2, Memory=4GB)

- **Volume Size**: 10GB

## Output Load Balancer DNS Name

- **Load Balancer DNS Name**: http://udaci-webse-39suz29xc3au-680245169.us-west-2.elb.amazonaws.com/