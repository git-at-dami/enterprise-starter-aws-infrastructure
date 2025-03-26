# enterprise-starter-aws-infrastructure
step by step infra setup guide for enterprise, using terraform

#### storing all infrastructure state in Terraform Cloud as the source of truth, managed using terraform

* terraform workspaces are infrastructure automation pipelines responsible for automating certain aspects of infra, examples: github repositories, governance(teams and workspaces), networks, machine clusters
* terraform cloud is used for governance via RBAC for Team scoped resources and workspace management
