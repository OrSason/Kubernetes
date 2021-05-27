# Kuberntes - Weight tracker app deployment

 This repo contains script for deploying weight tracker app on k8s aks cluster 
 
 Weight tracker app repo 
        https://github.com/OrSason/Node-Weight-Tracker-k8s.git
 
 
 
 - app-deploy.yml - deploy a replica set with app
 - app-services.yml - route traffic to app's pods
 - config-map.yml - contains basic app's configuration 
 - *hidden secrets.yml  - store app and db secrets
 

## CD - Jenkinsfile
 - delete old pods
 - deploying new pods with updated image
 - display active pods


