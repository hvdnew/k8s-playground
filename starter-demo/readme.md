## Pre-requisite:
1. Install Docker
2. Install Minikube
3. Start Minikube cluster

## Start a local K8s driven application

### Deploy a database
- Create a config set <mongo.config.yaml>
- Create a secrets config <mongo-secret.yaml>
- Create deployment and service for mongoDB <mongo.yaml>
- Create deployment and seervice for webapp
- Pass config and secret to webapp

- NEED TO TROUBLESHOOT THE WEBAP AS IT IS NOT RUNNING AGAINST THE DB.