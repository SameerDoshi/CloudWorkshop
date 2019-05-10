# Welcome to the Cloud Workshop!

## Quick Links:
- [Azure Portal](https://portal.azure.com)
- [Teams Meeting]()

## Demos Instructions:
1. [Create a Resource Group](##create-a-resource-group)
2. Create a Virtual Machine
3. Configure IIS
4. Configure a Network Security Group
5. Create an Azure Web Site
6. Create a budget


## Create a Resource Group
1. Login to the [Azure Portal](https://portal.azure.com) with your company email address.
2. Click on "Cloud Shell" Icon at the top right of the Azure portal ![Open Cloud Shell](./images/1-open-cloud-shell.png)
3. Select PowerShell as your default language. ![select PowerShell](./images/2-set-powershell.png)
4. Select a subscription to store cloud shell data (less than 5 MB of data will be stored). ![set subscription](./images/3-set-subscription.png)
5. After a few seconds Cloud Shell will initialize. 
6. Click into Cloud Shell and enter the command: `az group create --name RG-<yourname> --location central-us` and hit enter

![command](./images/4-create-rg.png)

7. The command will return json if sucessfull 
###Verify Resource Group Creation
8.  On the left menu bar click the `Resource Groups` button and search for your Resource Group ![search](./images/5-click-in-portal.png)