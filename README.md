# TechCo Website Project

CLCM3504: Continuous Integration and Continuous Deployment for Cloud Applications Course Project

## Table of Contents
- [TechCo Website Project](#techco-website-project)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
    - [Local Development](#local-development)
    - [CI/CD Setup](#cicd-setup)
    - [Terraform](#terraform)
  - [License](#license)
## Project Overview

As an entry-level member of a technology-focused program, your mission is to build a simple business website for a fictional company named "TechCo." The website will include four main pages: Home, About Us, Services, and Contact Us. In addition to creating the website, you will host it on an Amazon EC2 instance and showcase the implementation of continuous integration and continuous deployment (CI/CD) using Git, GitHub Actions, and Terraform.

## Prerequisites

- Apache Web Server
- Terraform

## Getting Started
### Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/Rani2909/Group4CLCM3504.git
   cd your-project
   ```
2. Install Apache Web server:
   ```bash
   ## For Ubuntu
   sudo apt-get install apache2

   ## For Linux
   sudo yum install httpd
   ```
### CI/CD Setup

- GitHub Actions is the thing that use in this project [link](https://github.com/Rani2909/Group4CLCM3504/blob/main/.github/workflows/Git2EC2.yml)

- Setting the sercret variables in GitHub `EC2_SSH_KEY `, `HOST_DNS`, `USERNAME`, `USERNAME`

### Terraform

1. Install Terraform:
   - Follow the [official Terraform installation guide.](https://learn.hashicorp.com/tutorials/terraform/install-cli)
2. Navigate to the `terraform` directory:
   ```bash
   cd terraform
   ```
3. Initialize Terraform:
   ```bash
   terraform init
   ```
4. Review and apply the Terraform configuration:
    ```bash
    terraform apply
    ```
## License
This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.
