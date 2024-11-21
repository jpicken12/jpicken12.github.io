2024-07-24 16:32

Status:

Tags: #Azure-PowerShell #az-900 

# Azure PowerShell

Azure PowerShell is a set of cmdlets for managing Azure resources from the PowerShell command line. 

There was a question on one of the AZ-900 practice tests which asked:

>An IT administrator for a company has been given a PowerShell script. This PowerShell script will be used to create several Virtual Machines in Azure. You have to provide a machine to the IT administrator for running the PowerShell script. You decide to provide a Linux machine that has the Azure CLI tools with PowerShell 5.x installed. Would this solution fit the requirement?

I answered yes, because PowerShell is installed, but the following is true:

- Azure PowerShell works with PowerShell 5.1 on Windows
- PowerShell 6.2.4 and later is compatible on all OS platforms
- Microsoft recommends PowerShell 7.x

So the answer to the above question is no, because PowerShell 5.x is not supported on Linux.
# References
Source: https://www.whizlabs.com/learn/course/microsoft-azure-certification-az-900/256/quiz/14909/report/7983720