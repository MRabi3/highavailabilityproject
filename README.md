## High availabilty project
in project starter you will find 4 files, as mentioned in the script in end of this read me file, these files help you to create demoserver with it's infrastructure and load balancer, high availability environment.



![High Availablility Project](https://user-images.githubusercontent.com/15274589/172032714-85c43542-f550-4058-892c-8ffbb71a07b1.png)



### Dependencies
##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.
you have generated a key pair file, and add the file in the demoserver script.

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).




### How to run the supporting material?
You can run the supporting material in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.bat file
./create.bat infrastructure infrastructure.yml infrasctructure-parameters.json
./create.bat demo-servers demoserver.yml demoserver-parameters.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./update.bat infrastructure infrastructure.yml infrasctructure-parameters.json
./update.bat demo-servers demoserver.yml demoserver-parameters.json
```
