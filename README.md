# AWS CLOUD SOLUTION FOR 2 COMPANY WEBSITES USING A REVERSE PROXY TECHNOLOGY

The sole aim of this project to build the infrastructure in AWS. Here we will build a secure infrastructure inside AWS VPC (Virtual Private Cloud) network for a fictitious company that uses WordPress CMS for its main business website, and a Tooling Website for their DevOps team. As part of the company's desire for improved security and performance, a decision has been made to use a reverse proxy technology from NGINX to achieve this. This repository further contains the scripts for setting up configuration for nginx, bastion, tooling and wordpress servers in setting up my company cloud infrastructure


`Cost, Security, and Scalability are the major requirements for this project. Hence, implementing the architecture designed below;`

## Project Architecture Diagram

![Architecture diagram](/images/AWScloudup-Architecture.PNG)

## Project Kick-off

Properly configure your AWS account and Organization Unit. [Watch How To Do This Here](https://youtu.be/9PQYCc_20-Q)

- Create an AWS Master account. (Also known as Root Account)

- Within the Root account, create a sub-account and name it DevOps. (You will need another email address to complete this)

- Within the Root account, create an AWS Organization Unit (OU). Name it Dev. (We will launch Dev resources in there) Move the DevOps account into the Dev OU.

- Login to the newly created AWS account using the new email address.

- Create a free domain name for your fictitious company at Freenom or any other domain registrar such as namecheap or godaddy.

- Create a hosted zone in AWS, and map it to your free domain from Freenom. [Watch how to do that here](https://youtu.be/IjcHp94Hq8A)

## Infrastructure Set-up
