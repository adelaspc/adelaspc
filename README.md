# Hi, I'm Adela 👋

**Chemistry Researcher ➔ Cloud & DevOps Engineer**  
Combining an analytical research mindset with hands-on expertise in cloud infrastructure, containerization, and automation.

🌐 **Live Portfolio & Demos:** [app.infractl.dev](https://app.infractl.dev/)

---

### Certifications
* **AWS Certified Solutions Architect – Associate** ➔ [View Credential](https://www.credly.com/badges/4131f9b7-71ee-4adf-9d4e-4754e9d3b649/public_url)

---

### Core Focus
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

---

### Technical Skills

| Category | Skills & Tools |
| :--- | :--- |
| **Cloud Infrastructure** | **AWS** (EC2, VPC, IAM, S3, CloudFront, RDS, ECR, ALB, CloudWatch) |
| **Infrastructure as Code** | **Terraform** · Helm · Kubernetes Manifests |
| **Containers & Orchestration** | **Docker** · Docker Compose · **Kubernetes** |
| **CI/CD & Automation** | **GitHub Actions** · OIDC · Automated Testing & Deployment |
| **Scripting & Backend** | **Python** · **Bash** · Flask · MySQL |
| **Security & Observability** | Trivy · Checkov · Structured Logging · Secrets Management |
---

## Featured Projects

### AWS 3-Tier Architecture

> Three-tier AWS architecture designed around network isolation, scalability, and secure communication between application layers.

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/adelaspc/aws-3tier-architecture.git)
[![Live Case Study](https://img.shields.io/badge/Case_Study-Live_Overview-2ea44f?style=flat&logo=googlechrome&logoColor=white)](https://app.infractl.dev/aws-3tier-architecture.html)

- Designed a multi-tier VPC architecture with public and private subnets
- Used an Application Load Balancer to distribute traffic across application instances
- Deployed the database layer with Amazon RDS in private subnets
- Managed infrastructure reproducibly with Terraform and security-focused network rules

**Tech:** `AWS` · `Terraform` · `VPC` · `EC2` · `ALB` · `RDS` · `IAM`

---

### AutoDeploy

> A Kubernetes-based deployment platform built to explore and automate modern application delivery.

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/adelaspc/autodeploy-platform)
[![Live Case Study](https://img.shields.io/badge/Case_Study-Live_Overview-2ea44f?style=flat&logo=googlechrome&logoColor=white)](https://app.infractl.dev/autodeploy-platform.html)

- **Deployment workflows**: Accepts manual deployment requests and GitHub webhook events, then processes them asynchronously through background workers.
- **Runtime support**: Deploys applications locally with Docker or to Kubernetes using Helm charts.
- **Lifecycle management**: Tracks deployment status and supports health checks, logs, stop operations, and runtime reconciliation.
- **Configuration**: Manages project settings, environment variables, resource limits, registry access, and Kubernetes deployment options.
- **Quality checks**: Uses GitHub Actions for automated tests, linting, dependency auditing, and security scanning.

**Tech:** `Docker` · `Kubernetes` · `Helm` · `GitHub Actions` · `MySQL` · `Python`

---

### AWS Static Website Infrastructure

> Terraform project for hosting a static website on AWS using a private S3 bucket and CloudFront.

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/adelaspc/static-website)
[![Live Case Study](https://img.shields.io/badge/Case_Study-Live_Overview-2ea44f?style=flat&logo=googlechrome&logoColor=white)](https://app.infractl.dev/static-website.html)

- **Infrastructure**: Provisions S3, CloudFront, ACM certificates, Cloudflare DNS records, access logging, and CloudWatch alarms.
- **Deployment**: Uses separate GitHub Actions workflows for Terraform changes and frontend deployments.
- **Authentication**: GitHub Actions accesses AWS through OIDC and temporary credentials.
- **Security**: Keeps the S3 origin private, restricts access through CloudFront OAC, redirects HTTP to HTTPS, and adds security headers.
- **Scope**: Designed as a low-cost, single-environment portfolio project.

**Tech:** `AWS` · `Terraform` · `CloudFront` · `S3` · `ACM` · `GitHub Actions` · `OIDC`

---

## Currently Focused On

- AWS architecture and cloud infrastructure
- Terraform and Infrastructure as Code
- Kubernetes and container orchestration
- CI/CD, cloud security, and observability

