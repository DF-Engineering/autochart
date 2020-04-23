# AutoChart
Deploy tool for rendering HELM charts templates based on an input values file. Charts are packages of pre-configured Kubernetes resources.

Use autochart to:
  - To run your dockerized application to run in Kubernetes environment
  - Create a configuration based deployment
  - Intelligently render and manage your Kubernetes manifest files
  - Manage multiple HELM release packages with changes only to values file
  
## AutoChart in a Nutshell

autochart is a tool that streamlines manifestation of HELM charts, to install and manage Kubernetes applications. 

While we work as a team, developing multiple Kubernetes application in a "continous-deployment" methodology; HELM deployment is like a "Gold" standard for Kubernetes deployments. However, in an organization where multiple teams are working on multiple application it is important to streamline the deployment.

## The Problem : 
Application developers create HELM charts for their applications based on a version available in their machine and may have custom changes to charts for application deployment. These charts become harder to manage and update, when new features are available in the latest version HELM and your charts or older version. 

## Solution : 
Self-rendered HELM charts using autochart. This tool is used to create our application deployment/service/ingress templates on the fly using a "HELM" latest standard, while gives the control to add or override chart templates using conditional parameters in HELM values file.


