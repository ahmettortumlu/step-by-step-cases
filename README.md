# step-by-step-cases
I was asking questions about development of Devops Engineers, many of them was need a guide. To help them i prepared a step by step cases.

This guide for intern or newly graduated Devops Engineers. 

# Step-1
Create an account at GCP, you can use 250 dollar credit from GCP.

# Step-2
At newly created GCP account using Terraform create a project, 
* give a custom project-id
* create a user group and user,
* Create a VPC at this VPC, use terraform modules.
* Decide a naming convention for your resources.
 
# Step-3
Create a custom image using packer.
* At this VM image install docker.
* For base image use Ubuntu 22.04 LTS Minimal.
* Deploy a node-exporter to monitor instances,
* Give a proper name to your VM image.


