**# Mediawiki**
Contains docker and kubernetes files for setting up the Mediawiki v1.34 service on Kubernetes cluster

##**Kubernetes**
The kubernetes objects are defined in following files: mediawiki-deployment.yaml mediawiki-service.yaml db-deployment.yaml db-service.yaml env-configmap.yaml wikinetwork-networkpolicy.yaml secret.yaml

**Deploying the Stack**
On the Kubernetes Clustet, run command:

kubectl apply -f mediawiki-deployment.yaml,mediawiki-service.yaml,db-deployment.yaml,db-service.yaml,env-configmap.yaml,secret.yaml.

