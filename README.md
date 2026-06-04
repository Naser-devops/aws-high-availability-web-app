# aws-high-availability-web-app
Highly available AWS web infrastructure using EC2, ALB, Auto Scaling, and private/public subnets.
# AWS High Availability Web Application

## Project Overview

This project demonstrates a highly available and secure AWS web infrastructure architecture using multiple AWS services.

The infrastructure was designed to host a web application using private EC2 instances behind an Application Load Balancer while maintaining secure networking practices.

---

## Architecture Components

### Networking

* Custom VPC
* Public Subnets
* Private Subnets
* Internet Gateway
* NAT Gateway
* Route Tables

### Security

* Security Groups
* Bastion Host for secure SSH access
* Private EC2 instances without public IP addresses

### Compute & Scaling

* EC2 Instances
* Launch Template
* Auto Scaling Group (ASG)

### Load Balancing

* Application Load Balancer (ALB)
* Target Group
* Health Checks

### Web Server

* Ubuntu Server
* Nginx Web Server

---

## Architecture Flow

Internet → Application Load Balancer → Private EC2 Instances

The Application Load Balancer receives public traffic and distributes requests across private EC2 instances running Nginx.

---

## Key Features

✅ High Availability across multiple Availability Zones
✅ Secure private infrastructure
✅ Auto Scaling support
✅ Load Balancing
✅ Bastion Host architecture
✅ Production-style AWS networking setup

---

## Technologies Used

* AWS VPC
* AWS EC2
* AWS Auto Scaling
* AWS Application Load Balancer
* AWS Security Groups
* Ubuntu Linux
* Nginx

---

## What I Learned

Through this project I gained hands-on experience with:

* AWS Networking
* Public vs Private Subnets
* Linux Administration
* Load Balancers
* Auto Scaling Groups
* Bastion Host Architecture
* Cloud Security Basics

---

## Screenshots

(Add your screenshots here)

* AWS Architecture
* Load Balancer
* Target Group Health Checks
* Nginx Running Successfully

---

## Author

Naser

