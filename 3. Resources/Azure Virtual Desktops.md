2024-08-20 16:11

Status:

Tags: #azure/virtualDesktops #terraform 

# Azure Virtual Desktops
Create the following
- Modules
	- azureRm
		- virtualDesktop
			- configure a desktop
			- configure a host
			- configure rbac permissions
			- configure network settings
			- create azure files storage
			- create azure compute gallery
			- create log analytics workspace
## Tasks
- [x] Add main, outputs & variables tf files for each module
- [x] Create a main.tf that calls the modules
- [x] Create a tfvars to pass in the variable values to each module block
- [x] update the variable defaultsqwr


# References
Source: [[https://learn.microsoft.com/en-us/azure/developer/terraform/configure-azure-virtual-desktop]] 