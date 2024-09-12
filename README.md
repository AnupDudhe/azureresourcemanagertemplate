# azureresourcemanagertemplate  

### what is azureresourcemanagertemplate ? </br>
ARM Template is IAC tool providedd by azure cloud provider for 
cration of infrastructure using scripting template i.e scripts ,
the logic is generally written in json format.


### how to invoke azureresourcemanagertemplate using auzure cli ? </br>
to create a resource group you would require this command. 
```
az group create --name vscode --location 'Central US' 
```
#az group create --name resourcegroupname --location regionwherergwillbecreated

to invoke azureresourcemanagertemplate you would require this command

```
az deployment group create --resource-group vscode --template-file 01-storage-account.json
```
#az deployment group create --resource-group resourcegroupname --template-file azuretemplatename 



