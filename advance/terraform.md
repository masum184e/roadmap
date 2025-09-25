# Terraform Learning Roadmap

## 1. Introduction
- What is Infrastructure as Code (IaC)?
- Why Terraform? (vs CloudFormation, Pulumi, Ansible)
- Terraform Architecture
  - Core
  - Providers
  - State
- Installing Terraform (CLI basics)

## 2. Basics
- Writing your first `.tf` file
- Providers & Resources
- Variables & Outputs
- Data Sources
- Terraform Commands
  - `init`, `plan`, `apply`, `destroy`
  - `validate`, `fmt`, `graph`

## 3. State Management
- Terraform State (`terraform.tfstate`)
- Local vs Remote State
- State Locking
- Backends (S3, GCS, Azure Blob, Consul)
- State Management Commands (`state list`, `state mv`, `state rm`)

## 4. Variables & Expressions
- Input Variables
- Output Variables
- Locals
- Type Constraints (string, number, bool, list, map, object, tuple)
- Interpolation Syntax (`${}`)
- Conditional Expressions & Functions

## 5. Modules
- Creating and Using Modules
- Module Sources (Local, Git, Terraform Registry)
- Module Composition
- Variables & Outputs in Modules
- Best Practices for Module Design

## 6. Provisioners & Dependencies
- `null_resource`
- Provisioners (`local-exec`, `remote-exec`)
- Implicit vs Explicit Dependencies
- Lifecycle Rules (`create_before_destroy`, `ignore_changes`)

## 7. Advanced Terraform
- Workspaces (multi-environment management)
- Dynamic Blocks
- for_each vs count
- `depends_on` usage
- Data Transformation Functions
- Templating with `templatefile`

## 8. Remote Backends & Collaboration
- S3/DynamoDB Backend (AWS)
- Remote State with Terraform Cloud
- Remote Execution
- Team Collaboration & State Sharing

## 9. Testing & Validation
- `terraform validate`
- `terraform fmt`
- Sentinel Policies (Policy as Code)
- Terratest (Golang-based testing)
- Checkov & tfsec (Security scanning)

## 10. Infrastructure Scaling
- Multi-Cloud Deployments
- Hybrid Cloud Use Cases
- Terraform with Kubernetes
- Terraform with Docker
- Managing VPCs, EC2, S3, IAM with Terraform (AWS example)

## 11. CI/CD & Automation
- Terraform in GitHub Actions / GitLab CI / Jenkins
- Automated Plan & Apply
- Approval Workflows
- GitOps with Terraform

## 12. Security & Best Practices
- Secrets Management (Vault, SSM, AWS Secrets Manager)
- Least Privilege for Terraform IAM Roles
- Avoiding Hardcoded Secrets
- State Encryption
- Code Organization & Naming Conventions

## 13. Performance & Scaling
- Large Terraform Projects
- Dependency Graph Optimization
- Using `-target` for partial applies
- Refactoring State Safely

## 14. Ecosystem & Tools
- Terraform Cloud & Enterprise
- Atlantis (Automated Terraform in Pull Requests)
- Terragrunt (DRY Config Management)
- OpenTofu (Terraform fork, open governance)

## 15. Certification (Optional)
- HashiCorp Certified: Terraform Associate

---
✅ Suggested Path:
- **Beginner:** Basics → Providers & Resources → Variables & Outputs → State → Modules  
- **Intermediate:** Workspaces → Backends → Dependencies → Provisioners → Testing  
- **Advanced:** CI/CD → Security → Multi-Cloud → Performance → Ecosystem Tools
