Azure CLI Commands

#ResourceGroup
az group create --name 'Prasanna-RG' --location 'eastus'

#App Service plan
az appservice plan create --resource-group 'Prasanna-RG' --name PrasannaAppPlan --sku B3

#App Service
az webapp create --resource-group 'Prasanna-RG' --plan 'PrasannaAppPlan' --name 'prasannademowebsite'
