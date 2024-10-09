<<<<<<< HEAD
# Container-orchestration-11
=======
# MERN Stack Kubernetes Deployment and HELM Chart

## Overview

This project is designed to deploy a MERN (MongoDB, Express.js, React.js, Node.js) stack application using Kubernetes, HELM, and Jenkins for automation. The application is composed of separate frontend and backend components. This setup includes Kubernetes deployment files, a HELM chart for easier management, and Jenkins automation to streamline the build and deployment processes.

## Project Structure

1. **Frontend (FE)**
   - **Repository**: [learnerReportCS_frontend](https://github.com/UnpredictablePrashant/learnerReportCS_frontend)

2. **Backend (BE)**
   - **Repository**: [learnerReportCS_backend](https://github.com/UnpredictablePrashant/learnerReportCS_backend)

## Requirements

- **Kubernetes Cluster**: Minikube, EKS, AKS, or another Kubernetes service
- **Helm CLI**: For managing Kubernetes applications
- **Jenkins**: For continuous integration and deployment
- **Docker**: For building container images
- **Git**: For version control

## Getting Started

### 1. Kubernetes Deployment Files

- Create backend, Frontend and Mongo DB deployment and service file with ClusterIP

### 2. Jenkins Setup

- Create a New Pipeline Job in Jenkins.
- Configure the Job to use the provided Jenkinsfile.
- Add Jenkins Credentials for Docker registry and Kubernetes.

## Conclusion
- This repository provides a complete solution for deploying a MERN stack application using Kubernetes, HELM, and Jenkins. It includes deployment files, HELM chart configurations, and Jenkins automation scripts to simplify the deployment process.
- For additional help, refer to the following documentation:

```

- Kubernetes Documentation
- Helm Documentation
- Jenkins Documentation

```
>>>>>>> 2446d7a (.)
