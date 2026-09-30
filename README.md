# Hi 👋, I'm Sowmya Sree

### Cloud & DevOps | AWS | Terraform | Docker | CI/CD

I'm a Cloud & DevOps professional focused on building and automating cloud infrastructure, CI/CD pipelines, containerized applications, and AWS deployment workflows.

I enjoy working with **AWS, Terraform, Docker, GitHub Actions, Git, Linux, and CI/CD automation**, and I'm currently deepening my skills in cloud infrastructure, container orchestration, and DevOps practices.

---

## 🚀 Cloud & DevOps Projects

### 1. End-to-End Java CI/CD, Containerization & AWS Deployment

**Java 17 | Maven | GitHub | GitHub Actions | Docker | Amazon ECR | Amazon ECS/Fargate | IAM/OIDC | Terraform**

Built an end-to-end deployment workflow for a Java-based application, covering application build, containerization, image management, and AWS deployment.

**Architecture**

```text
Developer
   ↓
GitHub
   ↓
GitHub Actions
   ↓
Maven
   ↓
JAR
   ↓
Docker Image
   ↓
Amazon ECR
   ↓
Amazon ECS / Fargate
   ↓
Java Application
```

**Key implementation:**

* Worked on Java application and generated the JAR artifact using **Maven**
* Created a **Docker image** containing the Java application and runtime.
* Automated build and deployment using **GitHub Actions**.
* Pushed container images to **Amazon ECR**.
* Deployed the application using **Amazon ECS with Fargate**.
* Configured ECS cluster, task definition, service, networking, and IAM roles.
* Implemented **GitHub OIDC with AWS IAM** to avoid using long-lived AWS access keys in GitHub Actions.
* Used **Terraform** to manage AWS infrastructure and imported existing AWS resources into Terraform state.

**What I learned:**

CI/CD automation, Docker containerization, ECR, ECS/Fargate, IAM/OIDC authentication, AWS deployment workflows, and Terraform infrastructure management.

---

### 2. AWS Infrastructure Automation with Terraform

**Terraform | AWS EC2 | VPC | S3 | IAM | Security Groups | ALB**

Built an AWS infrastructure project using **Terraform Infrastructure as Code** to replace manual AWS console-based provisioning with repeatable configuration.

**Architecture**

```text
Terraform
   ↓
AWS Infrastructure
   ├── VPC
   ├── Subnets
   ├── Security Groups
   ├── EC2
   ├── S3
   └── Application Load Balancer
```

**Key implementation:**

* Defined AWS infrastructure using **Terraform resource blocks**.
* Configured AWS networking and security components.
* Provisioned resources such as **EC2, S3, VPC, Security Groups, and ALB**.
* Used Terraform workflow:

```text
terraform init
       ↓
terraform plan
       ↓
terraform apply
```

* Worked with **Terraform state** to track managed infrastructure.
* Used resource dependencies to control infrastructure creation order.
* Used `terraform plan` to identify differences between Terraform configuration and existing infrastructure.

**What I learned:**

Infrastructure as Code, Terraform state management, resource dependencies, infrastructure lifecycle management, and migration of existing AWS infrastructure into Terraform.

---

### 3. AWS CI/CD Pipeline Implementation

**AWS CodePipeline | AWS CodeBuild | AWS CodeDeploy | GitHub | EC2**

Implemented a CI/CD pipeline using AWS-managed DevOps services to automate application build and deployment.

**Pipeline**

```text
GitHub
   ↓
AWS CodePipeline
   ↓
AWS CodeBuild
   ↓
Build / Package
   ↓
AWS CodeDeploy
   ↓
EC2
   ↓
Application
```

**Key implementation:**

* Connected the source repository with **AWS CodePipeline**.
* Used **AWS CodeBuild** for the application build process.
* Configured build instructions using **buildspec.yml**.
* Used IAM service roles to allow AWS services to perform required operations.
* Used **AWS CodeDeploy** for application deployment to EC2.
* Monitored pipeline executions and investigated build/deployment failures through logs and AWS configuration.
* Worked with environment/configuration values without hardcoding sensitive information into build configuration.

**What I learned:**

AWS-managed CI/CD, CodePipeline orchestration, CodeBuild, CodeDeploy, build specifications, IAM roles, deployment automation, and CI/CD troubleshooting.

---

## 🛠️ Technologies & Tools

### Cloud

`AWS` `EC2` `VPC` `IAM` `S3` `ECR` `ECS/Fargate` `ALB`

### DevOps

`CI/CD` `GitHub Actions` `Docker` `Terraform` `Linux` `Shell Scripting`

### Version Control

`Git` `GitHub`

### Infrastructure as Code

`Terraform`

### Containerization

`Docker` `Amazon ECR` `Amazon ECS/Fargate`

### Fundamentals

`Kubernetes` `CloudWatch` `AWS CLI`

---

## 📌 What I'm Currently Focusing On

* ☁️ AWS Cloud Infrastructure
* 🔄 CI/CD Automation
* 🐳 Docker & Containerization
* 🏗️ Terraform & Infrastructure as Code
* 🔐 IAM & Secure Cloud Access
* ☸️ Kubernetes Fundamentals
* 🐧 Linux & Shell Scripting
* 🔧 DevOps Troubleshooting

---

## 🤝 Connect With Me

* 💼 LinkedIn: www.linkedin.com/in/sowmyasreebacha
* 📧 Email: [bsowmyasree2@gmail.com](mailto:bsowmyasree2@gmail.com)
* 💻 GitHub: [sowmyasree33](https://github.com/sowmyasree33)

---

### ☁️ Building. Automating. Learning. Improving.
