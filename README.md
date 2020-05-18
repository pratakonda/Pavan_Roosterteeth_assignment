"This is an Assignment for Rooster Teeth"

Auto-Scaled Service
Objective
Launch an auto-scaled service in Amazon's Virtual Private Cloud.
Be creative! This is your chance to showcase your experience with a particular language or tool.
Ideally, though, this should take no more than three days.
Guidelines
1. Create an executable script for deploying your service. This script should be configurable with
command line parameters and should return the IP or DNS name of your service. At a minimum
you'll need this script to create the following Amazon resources to support your service:
a. Autoscaling Group
b. Launch Configuration
c. Security Group(s)
d. Elastic Load Balancer (don't worry about ssl)
2. Automagically provision your instances with the tool / language of your choice. Each instance
should serve a static page with nginx.
3. Ensure that your service has sensible security group(s) and is publicly available.
4. Ensure that your service can withstand the termination of a node and auto-heal.
Note: When your script is ran, it needs to successfully create and provision the necessary resources
for your homework to be accepted.
Deliverables
GitHub repo containing your launch script, provisioning code and any other artifacts.
Extra Credit
Use CloudWatch metrics to automatically scale your service based on CPU or request load.



* Clone the repository Pavan_Roosterteeth_assignment
* Use the cloudformation templete "pavan_roosterteeth_assignment.yml" for buiding resources 
* This templete can be uploaded to create a stack in cloudformation service from AWS management console.
* You can use AWS cli to create stack using the command "aws cloudformation create-stack --stack-name <<desired stack name>> --template-body file://pavan_roosterteeth_assignment.yml --parameters file://parameters.json"


