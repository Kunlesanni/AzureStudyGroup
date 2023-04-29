# AZURE STUDY GROUP SESSION GUIDE

## Cloud Computing Services and Benefits

* Identify the benefits of cloud computing, such as:
    * [High Availability](https://docs.microsoft.com/en-us/azure/architecture/checklist/availability)
    * [Scalability](https://docs.microsoft.com/en-us/azure/architecture/framework/scalability/design-scale)
    * [Elasticity](https://azure.microsoft.com/en-ca/overview/what-is-elastic-computing/)
    * [Agility](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/strategy/business-outcomes/agility-outcomes)
    * [Disaster Recovery](https://docs.microsoft.com/en-ca/azure/site-recovery/site-recovery-overview)
* Describe the Principles of Economies of Scale [(PDF)](https://download.microsoft.com/download/6/e/4/6e4cb3d1-5004-4024-8d90-6c66c83c17aa/the_economics_of_the_cloud_white_paper.pdf)
* Identify the differences between:
    * [Capital Expenditure (CapEx) vs. Operational Expenditure (OpEx)](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/strategy/business-outcomes/fiscal-outcomes#capital-expenses-and-operating-expenses)
    * [OpEx vs. CapEx: The Real Cloud Computing Cost Advantage](https://www.10thmagnitude.com/opex-vs-capex-the-real-cloud-computing-cost-advantage/)
* Describe the [consumption-based model](https://docs.microsoft.com/en-us/azure/architecture/framework/cost/design-price)

## Describe the differences between categories of cloud services

* Describe the [shared responsibility model](https://docs.microsoft.com/en-us/azure/security/fundamentals/shared-responsibility)
* Describe [Platform-as-a-Service (PaaS)](https://azure.microsoft.com/en-ca/overview/what-is-paas/)
* Describe [Software-as-a-Service (SaaS)](https://azure.microsoft.com/en-ca/overview/what-is-saas/)
* Describe [Infrastructure-as-a-Service (IaaS)](https://azure.microsoft.com/en-ca/overview/what-is-iaas/)
* Describe [Serverless Computing](https://azure.microsoft.com/en-ca/overview/serverless-computing/)
* Describe [Software-as-a-Service (SaaS)](https://azure.microsoft.com/en-ca/overview/what-is-saas/)
* Identify a [service type](https://azure.microsoft.com/en-ca/overview/types-of-cloud-computing/) based on a use case

## Describe the differences between types of cloud computing

* Define [Cloud Computing](https://azure.microsoft.com/en-us/overview/what-is-cloud-computing/)
* Describe [Public cloud](https://azure.microsoft.com/en-ca/overview/what-is-a-public-cloud/)
* Describe [Private cloud](https://azure.microsoft.com/en-ca/overview/what-is-a-private-cloud/)
* Describe [Hybrid cloud](https://azure.microsoft.com/en-ca/overview/what-is-hybrid-cloud-computing/)
* Compare and contrast the [3 types of cloud computing](https://azure.microsoft.com/en-us/overview/what-are-private-public-hybrid-clouds/)

## Hands-on study material at Microsoft Learn (Azure)

* [Describe core Azure concepts](https://docs.microsoft.com/en-us/learn/paths/az-900-describe-cloud-concepts)

## Hands-on study material at Microsoft Learn (Power Platform)

* [Microsoft Power Platform Fundamentals](https://learn.microsoft.com/en-us/training/paths/power-plat-fundamentals/)

## Hands-on study material at Microsoft Learn (Dynamics 365)

[LEARNING PATH](https://learn.microsoft.com/en-us/certifications/d365-fundamentals-customer-engagement-apps-crm/?tab=tab-learning-paths#certification-exams)

* [Microsoft Dynamics 365 customer engagement apps](https://learn.microsoft.com/en-us/training/paths/examine-core-capabilities-of-microsoft-dynamics-365-customer-engagement-apps/)
* [Fundamentals of Dynamics 365 Marketing](https://learn.microsoft.com/en-us/training/paths/learn-fundamentals-of-microsoft-dynamics-365-marketing/)
* [Fundamentals of Microsoft Dynamics 365 Sales](https://learn.microsoft.com/en-us/training/paths/learn-fundamentals-of-microsoft-dynamics-365-sales/)
* [Fundamentals of Microsoft Dynamics 365 Customer Service](https://learn.microsoft.com/en-us/training/paths/learn-fundamentals-microsoft-dynamics-365-customer-service/)
* [Fundamentals of Microsoft Dynamics 365 Field Service](https://learn.microsoft.com/en-us/training/paths/learn-fundamentals-of-microsoft-dynamics-365-field-service/)



## Video Links Below

* [Class 1](https://drive.google.com/file/d/111bRRRaig9NjuonBnOIglPo8XsEqffcj/view?usp=share_link)
* [Class 2](https://drive.google.com/file/d/1TfPwqix-Vtu2onFqMLuKt_Zf_ji7HPT2/view?usp=share_link)
* [Class 3](https://drive.google.com/file/d/1rquUQ04s2FJoAJPZh_qImJiMmdw0qO24/view?usp=share_link)
* [Class 4](https://drive.google.com/file/d/1LPKYsEm_0BTx8c9oyIwQksEwxHUg3oYI/view?usp=share_link)
* [Class 5](https://drive.google.com/file/d/1XUs6F5PUKxM0kvncvgl7UnHdM4tEz9_c/view?usp=share_link)


### Basic Azure Tips

* [Install Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
* [Install Az Powershell Module](https://learn.microsoft.com/en-us/powershell/azure/install-azure-powershell?view=azps-9.7.0)

#### Create a single Resource Group with Azure cli
```
az group create --name <name to give your Resource Group> --location <location>
```

#### Create Multiple Resource Groups with cli

```
# powershell create multiple resource groups and increment the name using a for loop

# login to azure

az login

# create a variable to hold the resource group name

$rgname = "ASG-RGS"

# create for loop to create multiple resource groups

for ($i=1; $i -le 5; $i++) {
    az group create --name $rgname$i --location eastus
}
```



[Return to Table of Contents](README.md)
