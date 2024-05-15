# README.md

## Repository Contents

This repository houses two primary projects:

1. **CI/CD Pipeline for Dockerized Flask Application**
   - `Jenkinsfile`: Defines the pipeline stages for building, testing, and deploying the Dockerized Flask application using Jenkins.
   - `Dockerfile`: Specifies the Docker image configuration for packaging the Flask application.
   - Flask application code: Contains the source code for the Flask application.
   - Configuration and setup scripts: Includes any necessary scripts or configurations for setting up the CI/CD pipeline environment.

2. **Terraform Configuration for AWS EC2 Instance**
   - `main.tf`: Defines the Terraform configuration for provisioning the AWS EC2 instance.
   - `providers.tf`: Configures the AWS provider.
   - `terraform.tfvars`: Contains variable values such as AMI ID, instance type, and subnet ID.
   - `variable.tf`: Declares input variables with descriptions.
   - `output.tf`: Specifies the output, typically the public IP address of the created EC2 instance.

### Author

Bairoju Saidachary

---

<i>Readme By <strong>@Saidachary</strong></i>
