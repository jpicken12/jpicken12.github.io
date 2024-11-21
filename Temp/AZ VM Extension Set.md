2024-07-22 11:19

Status:

Tags: [[az-900]] [[virtual machines]] [[configuration]]

# AZ VM Extension Set

Extensions are small applications that provide post-deployment configuration and automation tasks on Azure virtual machines.

This command is used to set extensions for a VM. For example, the tutorial on Microsoft learn uses the custom script extension to run a bash script on a vm. The script is stored in GitHub, installs NGINX and sets the homepage.

# References
Source: https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/3-exercise-create-azure-virtual-machine

Azure CLI Reference: https://learn.microsoft.com/en-us/cli/azure/vm/extension?view=azure-cli-latest

Az vm extension set documentation: https://learn.microsoft.com/en-us/cli/azure/vm/extension?view=azure-cli-latest#az-vm-extension-set