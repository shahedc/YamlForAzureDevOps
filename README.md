# YamlForAzureDevOps
YAML for Azure DevOps

Samples for deploying a web app to Azure App Service, via Azure DevOps Pipelines. 

### Basic

> File: _azure-pipelines.yml_

This is a basic example which builds and deploys the app in the same job, without taking advantage of the built-in mechanisms of the MultiStage Azure Pipelines.

### Multistage

> File: _azure-pipelines-multistage.yml_

This example shows how to use the MultiStage Pipelines, using a Job for the Build and a Deployment Job for the Release.

This would be the preferred way to do CI/CD.
