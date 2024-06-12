# Terraform Learning Map

## LEARN MAP

![map](./terraform.svg)

[CHECK THE INTERACTIVE MAP](https://sanix-darker.github.io/terraform_learn/terraform.html)

## CONCEPTS

- What is Terraform?
  - Infrastructure as Code (IaC)
  - Declarative language
- History of Terraform
- Installation
  - Using package manager (brew, apt, yum)
  - Downloading from HashiCorp

## Basic Concepts
- Infrastructure as Code
- Declarative Configuration
- Providers
- Resources
- State Management
  - State files
  - Remote state

## Configuration Language
- HCL (HashiCorp Configuration Language)
  - Syntax
  - Variables
    - Input variables
    - Output variables
  - Data types
- Terraform Blocks
  - Providers
  - Resources
  - Data sources
  - Outputs
- Terraform Commands
  - init
  - plan
  - apply
  - destroy

## Providers
- What are providers?
- Popular Providers
  - AWS
  - Azure
  - Google Cloud
  - Kubernetes
  - Docker
- Configuring Providers
  - Provider block
  - Authentication

## Resources and Data Sources
- Defining Resources
- Resource Attributes
- Meta-Arguments
  - depends_on
  - count
  - for_each
- Data Sources
  - Using data sources
  - Data source attributes

## Variables and Outputs
- Input Variables
  - Defining variables
  - Variable types
  - Default values
  - Variable files
- Output Variables
  - Defining outputs
  - Output values

## State Management
- Purpose of State
- State Files
- Remote State
  - Backends
    - Local
    - S3
    - Azure Storage
    - Google Cloud Storage
  - State locking
  - State versioning
- Managing State
  - terraform state commands
  - Importing existing resources

## Modules
- What are Modules?
- Creating Modules
- Using Modules
  - Module sources
  - Passing inputs to modules
  - Module outputs
- Public Module Registry
  - Terraform Registry

## Workspaces
- Introduction to Workspaces
- Using Workspaces
  - Creating workspaces
  - Switching workspaces

## Provisioners
- When to use Provisioners
- Common Provisioners
  - local-exec
  - remote-exec

## Advanced Concepts
- Templating with Terraform
  - Using the templatefile function
- Dynamic Blocks
- Terraform Functions
  - Built-in functions
  - Writing custom functions
- Managing Dependencies
  - Implicit and explicit dependencies
- Handling Secrets
  - Environment variables
  - Vault integration

## Best Practices
- Code Organization
- Version Control
- DRY (Don't Repeat Yourself) principle
- Module Reusability
- Security considerations
  - Storing secrets
  - IAM roles and permissions
- Testing
  - Using terraform validate
  - Integration testing with Terratest

## Integrations
- CI/CD with Terraform
  - GitHub Actions
  - GitLab CI
  - Jenkins
- Configuration Management
  - Ansible
  - Chef
  - Puppet

## Resources
- Official Documentation
- Tutorials and Courses
  - HashiCorp Learn
  - Udemy
  - Coursera
  - A Cloud Guru
- Books
  - "Terraform: Up & Running" by Yevgeniy Brikman
  - "Infrastructure as Code" by Kief Morris
- Online Communities
  - Terraform Discuss
  - Stack Overflow
  - Reddit (r/Terraform)
- Practice Projects
  - Deploying a web application
  - Setting up a VPC
  - Automating infrastructure provisioning

## Conclusion
- Keeping up-to-date
  - HashiCorp Blog
  - Release notes
  - Community events
