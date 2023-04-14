





## What is AMI?


##Difference between EC2 and AMI
The EC2 is used for creating the virtual server instance. The AMI is the EC2 virtual machine image.



## Steps to Creating a AMI

(IMAGE)

1. go to the aws console and type "EC2" in the search box
2. select your running instance
3. Click on the "Actions" - "Images and Templates - Create Image
4. Give your AMI a name: philip_tech221_nginx_ami
5. Write a description: need security with port 80 & ssh connection with port 22
6. Add a Tag (optional): this can be the same as the name

- To find your newly created AMI, Click on left hand dashboard - under AMIs - click on AMIs

- To launch an instance from you AMI:

1. Once you have found your created AMI, check the box beside your AMI
2. Click launch instance from ami
3. Complete steps to launch an instance - this time round you will be using the AMI you previously created.

## IAM role - controls permission


