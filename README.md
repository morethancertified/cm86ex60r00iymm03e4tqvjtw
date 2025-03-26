**Ticket Type:** Task  
**Title:** Access data from GitHub resources  
**Project:** Version Control System Deployment  
**Assignee:** You  
**Reporter:** Derek Morgan  
**Priority:** High  
**Labels:** Terraform, GitHub  
**Epic Link:** GitHub Expansion  
**Sprint:** Sprint 01/Dependencies

**Description:**

Create a `datasources.tf` file. Retrieve information about the current GitHub repository. If you are not in a repository, you'll need to create one. Retrieve the current GitHub user, and all information about the repository, the branch, and the directory tree. To do this, you should only hardcode the repository name once and use references for everything else required. The information should all be found in the plan or from the `terraform show` command

**Acceptance Criteria:**

> **Note:** If the `terraform validate` command fails, all tasks in the lab will fail!

1\. In a `datasources.tf` file, use data sources to retrieve all information.   
2\. Retrieve the username of the currently authenticated GitHub user.   
3\. Retrieve all information about the current or new GitHub repository.  
4\. Retrieve all information about the default branch.   
5\. Retrieve the directory tree.   
6\. Only hardcode the repository name ONCE. use references for all other required attributes. 

**Implementation Notes:**

- <a href="https://registry.terraform.io/providers/integrations/github/latest/docs" target="_blank">GitHub Provider Documentation</a>  
- <a href="https://developer.hashicorp.com/terraform/language/data-sources" target="_blank">Terraform Documentation</a>
