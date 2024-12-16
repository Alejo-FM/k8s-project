# K8s - Kubernetes
This project aims to create a Kubernetes cluster using Minikube and deploy a functional application.

## Team Members
- [**Alejandro Molina**](https://github.com/Alejo-FM)
- [**Daniel Bruno**](https://github.com/Holeekey)

## Requirements
<table style="margin: auto;">
  <tr>
    <td align="center" style="padding: 10px;">
      <img src="https://repository-images.githubusercontent.com/192628331/b6a28b00-9d24-11e9-8a4a-835c1d172ad9" width="80px;" style="border-radius: 50%;" alt="Minikube"/>
      <br />
      <a href="https://minikube.sigs.k8s.io/docs/start/"><strong>Minikube</strong></a>
    </td>
    <td align="center" style="padding: 10px;">
      <img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" width="100px;" alt="Docker Desktop"/>
      <br />
      <a href="https://docs.docker.com/desktop/"><strong>Docker Desktop</strong></a>
    </td>
  </tr>
</table>

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