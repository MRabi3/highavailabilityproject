## ND9991 - C2- Infrastructure as Code - Supporting Material and Starter Code
This folder provides the supporting material and starter code for the "ND9991 - C2- Infrastructure as Code" course. This folder contains the following folders:
1. project_starter - It contains the starter code.
2. supporting_material - It contains the essential files (.yml, .json, .bat, .sh, and .jpeg) that were referred in the different lessons of this course.

In addition to the current repo, there is one more repository, [nd9991-c2-Infrastructure-as-Code-v1-Exercises_Solution](https://github.com/udacity/nd9991-c2-Infrastructure-as-Code-v1-Exercises_Solution) that contains the solution to the exercises and video demos.  

![High Availablility Project](https://user-images.githubusercontent.com/15274589/172032714-85c43542-f550-4058-892c-8ffbb71a07b1.png)



### Dependencies
##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.
you have generated a key pair file, and add the file in the demoserver script.

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).

##### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com](www.lucidchart.com) is required to be able to draw the web app architecture diagrams for AWS.




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
