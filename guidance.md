# Deploy Cloud Foundry on Azure

In Microsoft Azure, there are serveral different environments, such as AzureCloud for global Azure and AzureChinaCloud for Azure operated by 21Vianet in China.

This document describes how to deploy [BOSH](http://bosh.io/) and [Cloud Foundry](https://www.cloudfoundry.org/) on [AzureCloud](https://azure.microsoft.com/en-us/) and [AzureChinaCloud](https://www.azure.cn/).

# 1 Prerequisites

You can create an Azure account according to the environment where Cloud Foundry will be deployed.

* [Creating an Azure account for AzureCloud](https://azure.microsoft.com/en-us/pricing/free-trial/)
* [Creating an Azure account for AzureChinaCloud](https://www.azure.cn/pricing/pia/)

<a name="get-started"/>
# 2 Get Started

## 2.1 Create a Service Principal

[**HERE**](./create-service-principal.md) is how to create a service principal.

## 2.2 Deploy BOSH and Cloud Foundry

You have two options to deploy BOSH and Cloud Foundry on Azure. One is ARM templates which can help you automatically prepare essential resources, the other is manual steps. Below shows the manual steps.


### 2.2.1 Manually

* [Deploy BOSH](./deploy-bosh-manually.md)
* [Deploy Cloud Foundry](./deploy-cloudfoundry-manually.md)


# 3 Additional Information

If you hit some issues when you deploy BOSH and Cloud Foundry, you can refer to the following documents. If it does not work, please open an issue.

* [Known issues](https://github.com/cloudfoundry-incubator/bosh-azure-cpi-release/blob/master/docs/additional-information/known-issues.md)
* [Troubleshooting](https://github.com/cloudfoundry-incubator/bosh-azure-cpi-release/blob/master/docs/additional-information/troubleshooting.md)
* [Migration from Preview 2](https://github.com/cloudfoundry-incubator/bosh-azure-cpi-release/blob/master/docs/additional-information/migration.md)
