## SETUP CONTINOUS DEPLOYMENT PIPELINE FOR A DOCKERIZED APPLICATION DEPLOYMENT USING CIRCLECI AND AMAZON EC2

This project sets up a continuous deployment pipeline using circleci to deploy containerized application directly to Amazon EC2.
In this project, we create an environmnet where changes to application code, upon commit to the main branch, would trigger a pipeline that deploys our application as a docker container instance on Amazon EC2 

### Getting Started

* Clone this repo: `git clone https://github.com/Fouty7/nodejs-kubernetes.git`
* Install Docker 
* Install Kubernetes via minikube
* Build Container using docker
* Configure kubernetes to run locally
* Deploy a container using Kubernetes and make a prediction