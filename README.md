## SETUP CONTINOUS DEPLOYMENT PIPELINE FOR A DOCKERIZED APPLICATION DEPLOYMENT USING CIRCLECI AND AMAZON EC2

This project sets up a continuous deployment pipeline using circleci to deploy containerized application directly to Amazon EC2.
In this project, we create an environmnet where changes to application code, upon commit to the main branch, would trigger a pipeline that deploys our application as a docker container instance on Amazon EC2 

### Getting Started / Summary

* Clone this repo: `git clone https://github.com/Fouty7/nodejs-kubernetes.git`
* Spin up Amazon EC2 Instance `https://docs.aws.amazon.com/efs/latest/ug/gs-step-one-create-ec2-resources.html`
* Create IAM User on AWS with programmatic access `https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html`
* Install Docker {ubuntu} `https://docs.docker.com/engine/install/ubuntu/`
* Create CircleCI Account
* Setup CircleCI for Continuous Deployment
* Setup Slack Integration for build pass/fail notification
* Build Container using docker