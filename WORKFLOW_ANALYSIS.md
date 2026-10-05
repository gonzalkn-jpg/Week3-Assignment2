# **Workflow Analysis**

## **What triggers this workflow to run?**
### This workflow begins to run when code changes are committed and pushed into main branch.
  
## **What are the four main steps this workflow performs?**
### 1. Checkout code: Gets the code from the repository
### 2. Validate HTML: Validates the HTML file(s)
### 3. Check links: Checks for any broken links
### 4. Upload artifact: Uploads the built site for deployment
  
## **What does the "Checkout code" step do and why is it necessary?**
### The "Checkout code" step retrieves code from the repository, which is necessary for the workflow
### to be able to check the code for any errors and/or broken links, and eventually get everything ready
### for deployment.
  
## **What is the purpose of the environment configuration?**
### The purpose of environment configuration is to set up where the resulting site will be deployed.
  
## **How does this automated deployment improve reliability compared to manual deployment?**
### Automated deployment is faster and significantly reduces the risk of human error.
  
## **What would happen if you pushed code to a different branch (not main)?**
### If code is pushed to a branch that is not main, the workflow will detect a conflict that must
### be resolved before the branch can be merged into the main branch.
