# Prueba Técnica Demo Devops Java

This is a simple application to be used in the technical test of DevOps.

## Diagrams

### Architecture Diagram
![arq diagram](https://github.com/user-attachments/assets/9575576b-c6e9-4375-8ef5-103c5d575fb4)


## Deployment

The application was deployed on both minikube and aws using kubernetes:
![image](https://github.com/user-attachments/assets/c85cc6d0-eb93-470f-936e-d69ed00c9b92)

## Description
To deploy the app, i created a set of yaml files:
  •	configmap.yaml
  •	secret.yaml
  •	deployment.yaml
  •	service.yaml
  •	ingress.yaml
  •	hpa.yaml

Also, I created a tf file to create infrastructure from code (IaC), and it is in Container/kubernetes/terraform/ path. To apply the file main.tf we shoud execute the following commands:
```bash
terraform init
```
```bash
terraform plan
```
```bash
terraform apply
```

El pipeline se encuentra en la pestaña Actions de éste repositorio o, accediendo directamente a este enlace: https://github.com/marlon-ulloa/demo-devops-java/actions/runs/12856621411.

Url Pública: https://load-1627607662.us-east-2.elb.amazonaws.com/api/swagger-ui.html



