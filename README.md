# 🚀 AWS 3-Tier Architecture using Terraform

<p align="center">

<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>

<img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white"/>

<img src="https://img.shields.io/badge/Infrastructure_as_Code-623CE4?style=for-the-badge"/>

</p>

---

# 📌 Project Overview

This project demonstrates a production-style AWS 3-Tier Infrastructure deployment using Terraform modules.

The infrastructure includes:

- VPC
- Public & Private Subnets
- Internet Gateway
- Route Tables
- EC2 Instances
- Application Load Balancer
- Security Groups

Built using modular Terraform architecture for scalability and reusability.

---

# 🏗️ Architecture Diagram

<p align="center">
  <img src="https://raw.githubusercontent.com/Mahendra0456/terraform-3tier-project-new/main/images/architecture.png" width="1000"/>
</p>

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Terraform | Infrastructure as Code |
| AWS | Cloud Provider |
| EC2 | Compute |
| VPC | Networking |
| ALB | Load Balancing |
| Security Groups | Security |

---

# 📂 Project Structure

```bash
terraform-3tier-project/
│
├── backend.tf
├── main.tf
├── outputs.tf
├── terraform.tfvars
├── variables.tf
│
├── modules/
│   ├── vpc/
│   ├── ec2/
│   ├── alb/
│   └── security-group/
│
└── README.md
