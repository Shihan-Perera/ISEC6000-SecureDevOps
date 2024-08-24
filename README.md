# ISEC6000 Secure DevOps - Assignment 1

## Project Name: ISEC6000-SecureDevOps

## Description

This project is part of the ISEC6000 Secure DevOps course assignment. The main objective of this project is to set up, deploy, and secure a microservices-based e-commerce application using industry-standard tools like Docker, Kubernetes, and Google Kubernetes Engine (GKE). This README file outlines the steps taken to complete the project and provides insights into the configurations and security measures implemented.

## Project Tasks

### Task 1: Set Up Initial Infrastructure

1. **Task 1.1: Create a Kubernetes Cluster**
   - Provisioned a Kubernetes cluster on Google Kubernetes Engine (GKE).
   - Configured the cluster with an appropriate name, region (asia-south1), and node pool settings.
   - Verified the cluster creation and ensured it's ready for deployment.

2. **Task 1.2: Configure `kubectl`**
   - Installed and authenticated `kubectl` on the local machine.
   - Configured `kubectl` to manage the Kubernetes cluster.
   - Verified connectivity and control over the Kubernetes cluster.

3. **Task 1.3: GitHub Repository Setup**
   - Created a GitHub repository named `ISEC6000-SecureDevOps`.
   - Initialized the repository with a README file.
   - Set up SSH keys for secure communication with GitHub.
   - Pushed the local project files to the GitHub repository.

### Task 2: Microservices Architecture and Deployment

- Deployed the Saleor e-commerce platform using Docker Compose within the Kubernetes environment.
- Customized the Docker Compose configuration to fit the project requirements.
- Verified the deployment by accessing the Saleor Dashboard and ensuring all services are running smoothly.

### Task 3: Implementing Security Measures

- Applied security best practices to Docker containers, such as running containers as non-root users and using secure base images.
- Performed vulnerability scanning on the container images using Trivy and documented the findings.

### Task 4: Architecture Visualization

- Created an architecture diagram that illustrates the interactions between the Saleor API, Dashboard, PostgreSQL, Redis, and other services.
- Annotated the diagram to highlight security measures and network policies.

### Task 5: Project Demonstration

- Conducted a project demonstration, showcasing the deployment process, security configurations, and overall functionality of the e-commerce platform.

## Prerequisites

- Docker
- Kubernetes
- Google Cloud SDK
- `kubectl` installed and configured
- Git and GitHub account

## Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:Shihan-Perera/ISEC6000-SecureDevOps.git
   cd ISEC6000-SecureDevOps
