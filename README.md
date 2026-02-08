
<div align="center">

  
# Hey, I'm Rihad✌️


### About Me

I am a DevOps engineer with proficiency in building and managing end to end deployments. Using tools displayed in my tech stack to ensure built environments are reliable, scalable, and require as minimal manual intervention as possible.

Always keen to learn and share regarding anything DevOps related!

---
### Tech Stack
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

---
### 🤝 Find me here

<p align="centre">
  <a href="https://www.linkedin.com/in/rihada" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>

---
### 👾 Check out my most recent projects


---
## [HedgeDoc EKS Project](https://github.com/rihad-a/hedgedoc-eks) &nbsp; ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white) ![Argo CD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

**I designed and automated a Kubernetes deployment for HedgeDoc, a collaborative markdown editor, with AWS infrastructure provisioned via Infrastructure-as-Code and deployed on AWS EKS.**

* **The Infrastructure:** Used **Terraform** to provision a modular AWS environment including a custom **VPC**, **Amazon EKS** with managed node groups, **RDS** for persistent data, **S3** for media storage, **IAM Pod Identity associations**, and **Route 53** DNS.
* **Pipelines:** Built **GitHub Actions** pipelines that handle everything from building and pushing **Docker** images to **ECR**, managing the full **Terraform** lifecycle, and dedicated **add/delete-resources** workflows.
* **The Security Layer:** Implemented **OIDC authentication** between GitHub Actions and AWS and integrated **External Secrets Operator** with **AWS Secrets Manager**.
* **GitOps & Observability:** Deployed **ArgoCD** to manage the application and used the **Kube-Prometheus-Stack** to give observe cluster health.
---


---

## [Threat Composer ECS Project](https://github.com/rihad-a/threat-composer-ecs) &nbsp; ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat&logo=terraform&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)


**I engineered an end-to-end deployment for the Threat Composer application to showcase a modern DevOps workflow. This project provides a fully automated "Infrastructure as Code" nature for the application.**

* **The Infrastructure:** Used **Terraform** to architect a modularized AWS environment including a custom **VPC** network, **ECS Fargate**, an **ALB**, and automated **Route 53** DNS.
* **The Pipeline:** Orchestrated **GitHub Actions** to manage the full Terraform lifecycle (Plan/Apply/Destroy) and Docker builds. Utilising **artifacts** for plan persistence, **TFLint/Checkov** for IaC compliance, and **Trivy** for container vulnerability scanning.
* **The Security Handshake:** Implemented **OIDC Authentication** between GitHub and AWS, eliminating the need for risky, outdated access keys.
---
