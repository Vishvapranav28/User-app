<<<<<<< HEAD
# User-app

# This is a Java SpringBoot Application

# Write a dockerfile for creating docker image
    -----> docker build -t user-app .

# Write yaml file for deploy into kubernetes
    -----> kubectl apply -f deployment.yaml
    -----> kubectl apply -f service.yaml

# To create and run a container
     docker run -d -p 8080:80 --name myconatiner myapp

# Write yaml file and deploy into kubernetes
     kubectl apply -f deployment.yaml 
     kubectl apply -f service.yaml

# To check pods info
    -----> kubectl get pods

# To get service
    -----> minikube service backend-service

=======
 This is a Java SpringBoot Application

# Write a dockerfile for creating  docker image
     docker build -t myapp .

# To create and run a container
     docker run -d -p 8080:80 --name myconatiner myapp

# Write yaml file and deploy into kubernetes
     kubectl apply -f deployment.yaml 
     kubectl apply -f service.yaml
    
# To check pods info
     Kubectl get pods
    
# To get service 
     minikube service backend-service
>>>>>>> fe4fde7 (first commit)
