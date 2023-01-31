### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the code for project 2- Deploy a high-availability web app using CloudFormation.

### Scenario
Your company is creating an Instagram clone called Udagram.

Developers want to deploy a new application to the AWS infrastructure.

You have been tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software.

This needs to be automated so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

The infrastucture can be seen in the diagram below

![alt text](https://github.com/lr53/nd9991-c2-Infrastructure-as-Code-v1/blob/master/project-2/img.png)

### How to run
#### Create Stack
```
./create.sh <stack name> network.yml network-parameters.json
./create.sh <stack name2> servers.yml server-parameters.json
```
#### Update Stack
```
./update.sh <stack name> network.yml network-parameters.jsoncd project-2
./update.sh <stack name2> servers.yml server-parameters.json
```

[link to project](http://proje-webap-1qfmahdb17trc-1400791864.us-east-1.elb.amazonaws.com/)