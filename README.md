# Deploying-a-Simple-Web-Application-on-AWS-EC2

This repository contains a step-by-step guide and scripts to deploy a basic web application on an AWS EC2 instance.

**Files:**

setup.sh: A shell script to set up an EC2 instance with Apache and deploy a sample HTML page.
sample-page.html: A simple HTML file used as the landing page.

**Steps to Deploy:**

Launch an EC2 instance in AWS and select an Amazon Linux AMI.
Configure security groups to allow HTTP traffic on port 80.
SSH into the instance and run the setup.sh script.
Access the application in a browser using the public IP of the instance.

**Real-Life Application:**

I deployed this setup to demonstrate a simple website hosting solution during a training session. It highlighted how AWS EC2 can provide a quick and cost-effective web hosting environment.
