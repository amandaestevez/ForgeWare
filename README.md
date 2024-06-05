# ![ForgeOps_banner](https://github.com/AleMorales9011/FORGE-OPS/blob/e1870a2dca92ea8c035b0f30b284d4afb019a498/src/images/Forge-ops_banner-removebg-preview.png)

## Bussines Case: DevOps Journey for SAAS Platform

## Objective

To walk you trough a common SAAS DevOps journey in a hands-on fashion trough a collection of scripts and diagrams that could be easily replicate for customized sitations. This project aims to illustrate:

1. User management, version control and inftractructure creation.
2. Infractstructure automation, and CI/CD pipelines.
3. Containerization and infrastucture management.

**Scenario:** Your company is a `rapidly growing` SAAS platform. You need to onboard new developers quickly. And efficiently, providing them with a fully functional development environment. And a `streamlined deployment` process.

**Challenges:**

1. Manual user and environment setup is `time-consuming` and error-prone.
2. Uncontrolled code versioning leads to `confusion and difficulty` in reverting changes.
3. Infrastructure provisioning is `slow and inconsistent`.
4. Deployments are manual and `prone to human error`.

## Example Usage

Script example that illustrate how to use IaC principles to **automate directory structures** within your infrastructure.

```bash
#!/bin/bash

# Creating directories
sudo mkdir /dir_1    # sudo execute the command with superuser privileges
sudo mkdir /dir_2    # mkdir is the command for creating a directory
sudo mkdir /dir_3
sudo mkdir /dir_4

# Creating groups
sudo groupadd GRP_1  # groupadd creates a new group
sudo groupadd GRP_2
sudo groupadd GRP_3

```

## Solution

We will implement a `fully automated` onboarding and deployment pipeline using the following scripts:

![DevOps_Journey](https://github.com/AleMorales9011/FORGE-OPS/blob/278e5fd944f771b2e465d0d554f45bdccdcbbccf/010-IMAGES/ForgeOps_Journey.png)

1.`Automating creation of users, directories, permissions and groups with Bash:`
This script will automate the creation of new developer accounts on the system, assign them directories and permissions based on their role, and add them to relevant development groups. This eliminates manual setup and ensures consistency.
`BEGINNER` `BASH` `LINUX`

2.`Implementing a version control system with Git/Github:`
We will use Git for version control and Github for a central repository. Developers will have access to the latest codebase and can track changes efficiently.
`BEGINNER` `GIT` `GITHUB`

3.`Deploying infrastructure with Terraform:`
Terraform will automate the provisioning of infrastructure like servers, databases, and storage on a chosen cloud platform. This ensures consistent and repeatable infrastructure deployment.
`INTERMEDIATE` `TERRAFORM` `CLOUD COMPUTING`

4.`Creation of CI/CD pipeline with Azure DevOps:`
Azure DevOps will be used to create a continuous integration and continuous delivery (CI/CD) pipeline. Upon code commit, the pipeline will automatically build, test, and deploy the application to a staging environment.
`INTERMEDIATE` `AZURE DEVOPS` `DEVOPS`

5.`Containerizing an application with Docker:`
The application will be containerized using Docker, creating a self-contained package with all dependencies. This promotes portability and simplifies deployments.
`INTERMEDIATE` `DOCKER` `LINUX`

6.`Deploying a web application with Kubernetes:`
Kubernetes will be used to orchestrate the deployment of Docker containers across multiple servers for scalability and high availability.
`ADVANCED` `KUBERNETES` `DOCKER`

7.`Automating Web App deployment with Bash`
A Bash script will trigger the Azure DevOps pipeline upon code commit, automating the entire deployment process.
`ADVANCED` `BASH` `LINUX` `AZURE DEVOPS`

8.`Setting developing environment with Vagrant:`
To provide developers with a consistent development environment locally, Vagrant will be used to create virtual machines pre-configured with all the necessary tools and dependencies.
`ADVANCED` `VAGRANT` `IAC`

## Final Infrastructure

Our end goal with this business case project is to be able to replicate a Software Engineering pipeline like the one in the image below.

![Final_Infrastructure](https://github.com/AleMorales9011/FORGE-OPS/blob/main/010-IMAGES/ForgeOps_final_infrastructure.png)

## Benefits

1. `Faster Onboarding:` Developers are up and running quickly with a pre-configured environment.
2. `Reduced Errors:` Automated provisioning and deployment minimize human error.
3. `Improved Version Control:` Git ensures proper code tracking and collaboration.
4. `Scalable Infrastructure:` Terraform and Kubernetes handle scaling needs.
5. `Efficient Delivery:` CI/CD pipeline automates builds, tests, and deployments.
6. `Consistent Development Environments:` Vagrant provides a uniform development experience for everyone.

## Conclussion

This combination of scripts automates the entire development and deployment process, saving time, increasing efficiency, and reducing errors. This allows your team to focus on developing innovative features for your e-commerce platform.
