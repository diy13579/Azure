# Azure

This is to automatically send email updates of Azure VM usage

Quota list in Azure actually includes cpu cores of deallocated VMs

So, we need take the following steps to get what we want:

1. Get cpu cores of deallocated VMs
2. List Usage from Azure Quota
3. Remove deallocated cores from list usage
4. send email
