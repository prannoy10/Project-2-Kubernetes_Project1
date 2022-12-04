# Project2-Kubernetes_Project

We will deploy mongodb database and webapplication. Webapplication we will connect
to the mongodb database using external configuration data from configmap and the secret.

Finally we will make webapplication accessible externally from the browser.

Create 4 K8s config files.

1.ConfigMap with MongoDB database endpoint
2.Secret with username and password for mongodb
3.Deployment file for MongodDB application with internal service
4.Deployment file for our own Webapp with external service.
