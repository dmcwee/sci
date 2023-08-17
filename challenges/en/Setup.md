# Set Up Your Challenge Environment
You can stand up your own environment to run thought the various challenges. This series of challenges can be done in a short or long period of time, with some exceptions, so using a 90-day or 1-year tenant is possible.

## Request a Demo Environment
1. Go to [CDX OnRamp/Microsoft Demo Site](https://cdx.transform.microsoft.com)
1. Select the [My Tenants](https://cdx.transform.microsoft.com/my-tenants) option from the top menu
1. Click the [Create Tenant](https://cdx.transform.microsoft.com/my-tenants/create-tenant) button
    1. At the top of the screen you can choose either the 90-day or 1-year tenant option.
1. Find the **Microsoft 365 Enterprise Demo Content** option and click the *Create Tenant* button
    1. Accept the Terms of Use and continue
    1. The tenant will be provisioned with a default admin account as well as numerous users and content.  For the purposes of these challenges these are the only identities and accounts you will need.
1. *Recommended:* Deploy the Azure Resource Group for this lab to your Azure Subscription (Yes and Azure Developer $150/mo subscription WILL support this lab) using the button in the 'Create your own Azure Resources' section below.

## Create your own Azure Resources
The below button will uses an Azure Resource Manager template to create an Azure Resource Group with the machines, networks, and other Azure resources you can use in some of the challenges.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdmcwee%2Fidamlab%2Fmaster%2FSCI%2Fazuredeploy.json)

### Requirements
1. Create a new Azure Resource Group, or choose one that you have already created.
2. Select an Azure Region close to you where the resources will be deployed. 
3. Provide an Admin password and be sure to save this.  You will need it for Challenges 8 and 9.

> !Note
>
> Each day at 7PM (1900) Eastern Standard Time the VM will automatically be shutdown.  You can change the automatic shutdown after the deployment has completed.

## Recommendations
The following recommendations are intended to make working in the lab easier for you.

1. Create a Profile in your Edge browser for your Admin account so you can easily save passwords, bookmarks, and generally get into the environment more quickly and easily.
2. Create a Second Profile in your Edge browser for the Megan Bowen account