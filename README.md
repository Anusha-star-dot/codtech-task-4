# CODTECH Internship Tasks – Combined
This repository includes documentation and automation for:
- Task 3: Kubernetes Deployment
- Task 4: SonarQube Security Scan Integration



\# CODTECH Task 3 - Microservices Kubernetes Deployment



This project demonstrates the deployment of a microservices-based application using Kubernetes.



\## 🔧 Structure



\- `backend/`: Backend service code and Dockerfile

\- `frontend/`: Frontend service placeholder

\- `k8s/`: Kubernetes deployment and service YAML files



\## 🚀 CI/CD



CI/CD is automated using \*\*GitHub Actions\*\*:

\- Docker build and push to Docker Hub

\- Kubernetes deployment using `kubectl`



\## 🐳 Docker Hub



Images are pushed to:  

📦 `docker.io/anushaice/backend:v1`



\## 🧪 How to Deploy



```bash

kubectl apply -f k8s/

kubectl get pods

kubectl port-forward svc/backend-service 5000:80

# CODTECH Internship - Task 4

## 🔐 Task Objective
Integrate a security scanning tool (SonarQube) with a CI/CD pipeline and generate a report for identified vulnerabilities.

## 📂 Repository Structure

codtech-task-4/
├── backend/
├── frontend/
├── .github/
│ └── workflows/
│ └── sonarqube.yml
├── README.md


## 🛠 Tools Used
- **GitHub Actions** – for CI/CD pipeline
- **SonarCloud** – for code analysis
- **Python** – for backend
- **YAML** – for workflow configuration

## 🚀 What It Does
- On every push to the `main` branch:
  - Triggers GitHub Actions workflow
  - Installs dependencies
  - Runs Python tests
  - Executes SonarCloud scan for code quality and security issues

## ✅ GitHub Action Workflows

- `Python CI` – Installs and tests Python code
- `SonarQube Analysis` – Scans code using SonarCloud

## 📊 SonarCloud Scan Result
Once the `SONAR_TOKEN` is configured in GitHub Secrets, the scan will produce a detailed report accessible on your SonarCloud dashboard.

## 🔗 Task 3 Reference
This task builds on SonarCloud setup from [Task-3 Repo](https://github.com/Anusha-star-dot/codtech-task-3)



## 👩‍💻 Author

**Anusha Manikonda**  
DevOps Engineer | Kubernetes | Docker | Azure | AWS  
📧 anusm170@gmail.com  
🔗 [GitHub](https://github.com/Anusha-star-dot) | [LinkedIn](https://linkedin.com/in/anusha-manikonda-33331993)



