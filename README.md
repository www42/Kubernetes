[![CloudShell](AzureFriday/img/launch-cloud-shell.png)](https://shell.azure.com/bash)

## Variables
```bash
RgName="Project42-RG"
Location="westeurope"
```

## Create a resource group
```bash
az group create --name $RgName --location $Location
```

<details><summary>Syntax</summary>

[Microsoft docs](https://docs.microsoft.com/en-us/cli/azure/group?view=azure-cli-latest#az-group-create)
</details>


## Create AKS cluster
```bash
az aks create --name $ClusterName \

```

<details><summary>Syntax</summary>

[Microsoft docs](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest#az-aks-create) 
</details>

<details><summary>What are AKS addons?</summary>

[Kubernetes Addons - Concept by Google](https://kubernetes.io/docs/concepts/cluster-administration/addons/)

[HTTP application routing](https://docs.microsoft.com/de-de/azure/aks/http-application-routing)

[Azure Monitor for containers overview](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/container-insights-overview)
</details>

