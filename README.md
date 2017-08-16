# Azure Automation Example
This is a example project copied from resources generated by azure cloud

# Requirements
* azure cli

# How to use it
```
az cloud set --name AzureChinaCloud
az login -u <account email> -p <account password>
az account set --subscription <subscirption name>
./deploy.sh -i "9e1e02d4-eb65-469b-a10b-4d19b55c20c5" -g "dcsp" -n testapp -l "China North"
```
