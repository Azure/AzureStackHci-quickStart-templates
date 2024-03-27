# Production Templates

This folder contains templates used by our partners to quickly provision or deploy an Azure Stack HCI Cluster through the Azure portal either using the [Deploy from cloud](https://ms.portal.azure.com/#view/Microsoft_Azure_HybridCompute/AzureArcCenterBlade/~/hciGetStarted) flow or thorugh [Deploy a custom template](https://ms.portal.azure.com/#create/Microsoft.Template) flow for the purpose of evaluating the infrastructure.

This folder can contain only 1 template for each model type (folder name) which is the tried and tested template. This template will be pre-selected by the UI when customers try to deploy arc machines with the same name. This is the default folder, and we are not allowing any versioning of template in the Production folder. 