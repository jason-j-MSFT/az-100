# AZ-100

## **Manage Azure subscriptions and resources (15-20%)**

### 1. Manage Azure subscriptions

* May include but not limited to: Assign administrator permissions; configure cost center quotas and tagging; configure Azure subscription policies at Azure subscription level
  
  1. **Azure account options** https://docs.microsoft.com/en-us/learn/modules/tour-azure-services-and-features/3-create-an-azure-account
  1. **Add or change Azure subscription administrators** https://docs.microsoft.com/en-us/azure/billing/billing-add-change-azure-subscription-administrator
  1. **What is Azure Cost Management?** https://docs.microsoft.com/en-us/azure/cost-management/overview-cost-mgt
  1. **How to optimize your cloud investment with Azure Cost Management** https://docs.microsoft.com/en-us/azure/cost-management/cost-mgt-best-practices
  1. **Use tags to organize your Azure resources** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-using-tags?toc=/azure/billing/TOC.json
  1. **Azure subscription and service limits, quotas, and constraints** https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits
  1. **What is Azure Policy?** https://docs.microsoft.com/en-us/azure/governance/policy/overview
  1. **Create and manage policies to enforce compliance** https://docs.microsoft.com/en-us/azure/governance/policy/tutorials/create-and-manage
  

### 2. Analyze resource utilization and consumption

* May include but not limited to: Configure diagnostic settings on resources; create baseline for resources; create and test alerts; analyze alerts across subscription; analyze metrics across subscription; create action groups; monitor for unused resources; monitor spend; report on spend; utilize Log Search query functions; view alerts in Log Analytics

  1. **What are Azure Monitor diagnostic logs** https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-overview-of-diagnostic-logs#what-are-azure-monitor-diagnostic-logs
  1. **Create, view, and manage metric alerts using Azure Monitor** https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/alert-metric
  1. **Manage alert instances** https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-alerts-managing-alert-instances?toc=/azure/azure-monitor/toc.json
  1. **Azure Monitor Metrics Explorer** https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-metric-charts?toc=/azure/azure-monitor/toc.json
  1. **Create and manage action groups in the Azure portal** https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-action-groups?toc=/azure/azure-monitor/toc.json
  1. **Monitoring usage and estimated costs** https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-usage-and-estimated-costs?toc=/azure/azure-monitor/toc.json
  1. **Collect and consume log data from your Azure resources** https://docs.microsoft.com/en-us/azure/monitoring-and-diagnostics/monitoring-overview-of-diagnostic-logs?toc=/azure/azure-monitor/toc.json
  1. **Analyze data usage in Log Analytics** https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-usage?toc=/azure/azure-monitor/toc.json
  1. **Get started with queries in Log Analytics** https://docs.microsoft.com/en-us/azure/log-analytics/query-language/get-started-queries?toc=/azure/azure-monitor/toc.json
  1. **Overview of the Azure agents to monitor Azure Virtual Machines** https://docs.microsoft.com/en-us/azure/monitoring/monitoring-overview-azure-agents?toc=/azure/azure-monitor/toc.json
  1. **Respond to events with Azure Monitor Alerts** https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-tutorial-response

### 3. Manage resource groups

* May include but not limited to: Allocate resource policies; configure resource locks; configure resource policies; implement and set tagging on resource groups; move resources across resource groups; remove resource groups

  1. **Lock resources to prevent unexpected changes** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-lock-resources
  1. **Create and manage policies to enforce compliance** https://docs.microsoft.com/en-us/azure/governance/policy/tutorials/create-and-manage
  1. **Use tags to organize your Azure resources** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-using-tags
  1. **Manage resource groups** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-portal#manage-resource-groups

## **Implement and manage storage (20-25%)**

### 4. Create and configure storage accounts

* May include but not limited to: Configure network access to the storage account; create and configure storage account; generate shared access signature; install and use Azure Storage Explorer; manage access keys; monitor activity log by using Log Analytics; implement Azure storage replication

  i.	**Configure network access to the storage account** https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security
  
  ii.	**Create and configure storage account** https://docs.microsoft.com/en-us/azure/storage/common/storage-quickstart-create-account?toc=%2Fazure%2Fstorage%2Fblobs%2Ftoc.json&tabs=portal
  
  iii.	**Generate shared access signature** https://docs.microsoft.com/en-us/azure/storage/common/storage-dotnet-shared-access-signature-part-1 
  
  iv.	**Install and use Azure Storage Explorer** https://docs.microsoft.com/en-us/azure/vs-azure-tools-storage-manage-with-storage-explorer?tabs=windows
  
  v.	**Manage access keys** https://docs.microsoft.com/en-us/azure/storage/common/storage-account-manage#access-keys
  
  vi.	**Monitor activity log by using Log Analytics** https://docs.microsoft.com/en-us/azure/azure-monitor/log-query/log-query-overview 
  
  vii.	**Implement Azure storage replication** https://docs.microsoft.com/en-us/azure/storage/common/storage-redundancy 

### 5. Import and export data to Azure

* May include but not limited to: Create export from Azure job; create import into Azure job; configure and use Azure blob storage; configure Azure content delivery network (CDN) endpoints

  i.	**Create export from Azure job** https://docs.microsoft.com/en-us/azure/storage/common/storage-import-export-data-from-blobs#step-1-create-an-export-job 

  ii.	**Create import into Azure job** https://docs.microsoft.com/en-us/azure/storage/common/storage-import-export-data-to-blobs#step-2-create-an-import-job 

  iii.	**Configure and use Azure blob storage** https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-portal 

  iv.	**Configure Azure content delivery network (CDN) endpoints** https://docs.microsoft.com/en-us/azure/cdn/cdn-create-new-endpoint 


### 6. Configure Azure files

* May include but not limited to: Create Azure file share; create Azure File Sync service; create Azure sync group; troubleshoot Azure File Sync 

  i.	**Create Azure file share** https://docs.microsoft.com/en-us/azure/storage/files/storage-how-to-create-file-share 
  
  ii.	**Create Azure File Sync service** https://docs.microsoft.com/en-us/azure/storage/files/storage-sync-files-deployment-guide?tabs=portal 
  
  iii.	**Create Azure sync group** https://docs.microsoft.com/en-us/azure/storage/files/storage-sync-files-deployment-guide?tabs=portal#create-a-sync-group-and-a-cloud-endpoint
  
  iv.	**Troubleshoot Azure File Sync** https://docs.microsoft.com/en-us/azure/storage/files/storage-sync-files-troubleshoot?tabs=portal1%2Cportal 


### 7. Implement Azure backup

* May include but not limited to: Configure and review backup reports; perform backup operation; create Recovery Services Vault; create and configure backup policy; perform a restore operation

  i.	**Configure and review backup reports** https://docs.microsoft.com/en-us/azure/backup/backup-azure-configure-reports 
  
  ii.	**Perform backup operation** https://docs.microsoft.com/en-us/azure/backup/quick-backup-vm-portal 
  
  iii.	**Create Recovery Services Vault** https://docs.microsoft.com/en-us/azure/backup/backup-azure-vms-first-look-arm#create-a-recovery-services-vault-for-a-vm 
  
  iv.	**Create and configure backup policy** https://docs.microsoft.com/en-us/azure/backup/backup-azure-vms-first-look-arm#defining-a-backup-policy 
  
  v.	**Perform a restore operation** https://docs.microsoft.com/en-us/azure/backup/backup-azure-arm-restore-vms 


## Deploy and manage virtual machines (VMs) (20-25%)

### 8. Create and configure a VM for Windows and Linux

* May include but not limited to: Configure high availability; configure monitoring, networking, storage, and virtual machine size; deploy and configure scale sets
  
  i.	**Configure high availability** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-availability-sets 
  
  ii.	**Configure monitoring, networking, storage, and virtual machine size**
  
    **Configure monitoring** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-monitoring 
    
    **Configure networking** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-virtual-network
    
    **Configure storage** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-manage-data-disk 
    
    **Configure virtual machine size** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-manage-vm#understand-vm-sizes 
    
  iii.	**Deploy and configure scale sets** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-create-vmss 

### 9. Automate deployment of VMs

* May include but not limited to: Modify Azure Resource Manager (ARM) template; configure location of new VMs; configure VHD template; deploy from template; save a deployment as an ARM template; deploy Windows and Linux VMs

  i.	**Modify Azure Resource Manager (ARM) template** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-the-portal#edit-and-deploy-the-template
  
  ii.	**Configure location of new VMs** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-the-portal#edit-and-deploy-the-template 
  
  iii.	**Configure VHD template** https://docs.microsoft.com/en-us/azure/marketplace/cloud-partner-portal/virtual-machine/cpp-deploy-json-template 
  
  iv.	**Deploy from template** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy 
  
  v.	**Save a deployment as an ARM template** https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-export-template#export-the-template-from-resource-group 
  
  vi.	**Deploy Windows and Linux VMs**
  
     **Windows VM using ARM template** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/ps-template
      
     **Linux VM using ARM template** https://docs.microsoft.com/en-us/azure/virtual-machines/linux/create-ssh-secured-vm-from-template 


### 10. Manage Azure VM

* May include but not limited to: Add data discs; add network interfaces; automate configuration management by using PowerShell Desired State Configuration (DSC) and VM Agent by using custom script extensions; manage VM sizes; move VMs from one resource group to another; redeploy VMs

  i.	**Add data discs** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/attach-managed-disk-portal 
  
  ii.	**Add network interfaces** https://docs.microsoft.com/en-us/azure/virtual-network/virtual-network-network-interface-vm 
  
  iii. **Automate configuration management by using PowerShell Desired State Configuration (DSC) and VM Agent by using custom script extensions** https://docs.microsoft.com/en-us/azure/virtual-machines/extensions/dsc-overview **and** https://docs.microsoft.com/en-us/azure/virtual-machines/extensions/custom-script-windows 

  iv.	**Manage VM sizes** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/resize-vm
  
  v.	**Move VMs from one resource group to another** https://docs.microsoft.com/en-us/azure/virtual-machines/windows/move-vm 
  
  vi.	**Redeploy VMs** https://docs.microsoft.com/en-us/azure/virtual-machines/troubleshooting/redeploy-to-new-node-windows 


### 11. Manage VM backups

* May include but not limited to: Configure VM backup; define backup policies; implement backup policies; perform VM restore

  i.	**Configure VM backup** https://docs.microsoft.com/en-us/azure/backup/backup-azure-vms-first-look-arm 
  
  ii.	**Define backup policies** https://docs.microsoft.com/en-us/azure/backup/backup-azure-vms-first-look-arm#defining-a-backup-policy 
  
  iii.	**Implement backup policies** https://docs.microsoft.com/en-us/azure/backup/backup-azure-vms-first-look-arm#initial-backup 
  
  iv.	**Perform VM restore** https://docs.microsoft.com/en-us/azure/backup/backup-azure-arm-restore-vms 


## Configure and manage virtual networks (20-25%)

### 12. Create connectivity between virtual networks

* May include but not limited to: Create and configure VNET peering; create and configure VNET to VNET; verify virtual network connectivity; create virtual network gateway

### 13. Implement and manage virtual networking

* May include but not limited to: Configure private and public IP addresses, network routes, network interface, subnets, and virtual network

### 14. Configure name resolution

* May include but not limited to: Configure Azure DNS; configure custom DNS settings; configure DNS zones

### 15. Create and configure a Network Security Group (NSG)

May include but not limited to: Create security rules; associate NSG to a subnet or network interface; identify required ports; evaluate effective security rules

## Manage identities (15-20%)

### 16. Manage Azure Active Directory (AD)

* May include but not limited to: Add custom domains; configure Azure AD Identity Protection, Azure AD Join, and Enterprise State Roaming; configure self-service password reset; implement conditional access policies; manage multiple directories; perform an access review

### 17. Manage Azure AD objects (users, groups, and devices)

* May include but not limited to: Create users and groups; manage user and group properties; manage device settings; perform bulk user updates

### 18. Implement and manage hybrid identities

* May include but not limited to: Install and configure Azure AD Connect; configure federation and single sign-on; manage Azure AD Connect; manage password sync and writeback
