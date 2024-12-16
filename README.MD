# K8s - Kubernetes
This project aims to create a Kubernetes cluster using Minikube and deploy a functional application.

## Team Members
- [**Alejandro Molina**](https://github.com/Alejo-FM)
- [**Daniel Bruno**](https://github.com/Holeekey)

## Requirements
- [**Minikube**](https://minikube.sigs.k8s.io/docs/start/)
- [**Docker Desktop**](https://docs.docker.com/desktop/)

## Commands availables

1. Clone the project
```bash
git clone https://github.com/Alejo-FM/k8s-project.git
```

2. Init the Minikube cluster
```bash
npm start
```

3. Check the status of the cluster
```bash
kubectl get all
```

4. Deploy the application
```bash
npm run services
```

5. Deploy only the backend
```bash
npm run service:backend
```

6. Deploy only the pgAdmin
```bash
npm run service:pg-admin
```

7. Delete the kluster
```bash
npm run delete
```