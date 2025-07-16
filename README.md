# MongoDB + Mongo Express on Kubernetes (Minikube)

This is a basic full-stack application deployed on Kubernetes using Minikube.  
It includes:

- A MongoDB database
- A Mongo Express UI
- Kubernetes deployments, services, secrets, and configmaps

## How to Run

1. Start Minikube:
   ```bash
   minikube start
   ```
2. Apply Kubernetes configs:
   ```bash
   kubectl apply -f mongodb/
   kubectl apply -f mongo-express/
   ```
3. Access Mongo Express:
   ```bash
   minikube service mongo-express-service
   ```

## Techstack

1.  Kubernetes
2.  Minikube
3.  MongoDB
4.  Mongo Express
