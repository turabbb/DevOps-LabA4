# Kubernetes Lab Application

A simple application deployed on Kubernetes cluster.

## Technologies Used
- Docker
- Kubernetes
- Python Flask
- GitHub Actions

## How to Run Locally
```bash
docker build -t kube-lab-app:v1 .
docker run -p 8080:8080 kube-lab-app:v1
```

Visit: http://localhost:8080