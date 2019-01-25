# Static Website Server Deployment in AWS using Ansible
##Ansible
###Ansible Playbook Roles:
  - Apache2
  - AWS_EC2_Infra Provision
  - Build customized AMI for auto scaling

###How to run Playbook:
  - Update awsenvvars.yml in files directory
  - Include created EC2 .pem file in files directory
  - Update main.yml in defaults in aws_ec2_infra role
  - Update main.yml in defaults in snapshot_ami_template role
  - Execute AWS_Apache2_WebServer_Infra.yml master playbook

##Python script for validating credit card numbers
###purpose:
  Evaluate given set of credit card numbers valid or invalid
###usage:
  python3 CreditCardNumberCheck.py <input value>
