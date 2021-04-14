# arm-example
This example shows how to deploy few resources using YAML pipelines and ARM template.

## Requirements / how to run
* Azure DevOps project
* Resource manager connection created in the Azure DevOps project, under project settings -> Pipelines / Service connections. Task parameter 'azureSubscription' in pipelines.deploy.json at line 8 must match the created connection name.
* This repository cloned or the files copied to another existing repository
* Pipeline created based on pipelines.yml in your Azure DevOps project. Pipelines from the left menu (blue rocket icon) -> New Pipeline -> Select your repository -> Select Existing Azure Pipelines YAML file -> /deploy/pipelines.yml -> Run
