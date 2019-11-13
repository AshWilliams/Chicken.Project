# Chicken.Project

> docker build -t ashwilliams/chicken-apache -f Dockerfile.apache .    
> docker run -it -p 8081:80 ashwilliams/chicken-apache    

> docker build -t ashwilliams/chicken-nginx -f Dockerfile.nginx .    
> docker run -it -p 8080:8080 ashwilliams/chicken-nginx    

> docker run -it -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts    
> docker exec -it  -u root `<container-id>` bash

> minikube start --vm-driver=none --extra-config=kubeadm.ignore-preflight-errors=SystemVerification    
> minikube tunnel    
> kubectl apply -f chicken-project.yaml --validate=false

> kubectl scale deployment.v1.apps/chicken-project --replicas=4
