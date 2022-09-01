# java-postgresql-arm

## Resources Created
This arm template will create the following resources
1. App Service Plan (Basic)
2. Web App (Java 11)
3. PostgreSQL Azure Database - Single Server, General Purpose 
4. GitHub Actions workflow file

# Deploy arm template (CLI)

## Steps to deploy
#### 1. Create resource group
```cli
az group create --name my-rg --location eastus
```

#### 2. Deploy arm template
```cli
az deployment group create --resource-group my-rg --template-file "path/to/file.json"
```
