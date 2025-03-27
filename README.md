# enterprise-starter-aws-infrastructure
step by step infra setup guide for enterprise, using terraform
* to save time and avoid doing the same thing twice

#### storing all infrastructure state in Terraform Cloud as the source of truth, managed using terraform and gitops(state changes defined via commits)

* terraform workspaces are infrastructure automation pipelines responsible for automating certain aspects of infra, examples: github repositories, governance(teams and workspaces), networks, machine clusters
* terraform cloud is used for governance via RBAC for Team scoped resources and workspace management
* terraform cloud provides a consistent execution environment for terraform code
* use terraform cloud to scale terraform practice within organization

## Terraform Basic/Fundamental Blocks
* Terraform Settings Block
* Terraform Provider Block
* Terraform Resource Block

provider configurations belong to root module, not child module
