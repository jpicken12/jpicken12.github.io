2024-07-27 10:19

Status:

Tags: #String-Interpolation #bash #Azure-CLI 

# Bash String Interpolation

String interpolation in bash uses $(....). For example, when used with [[Azure Command Line Interface]] from BASH shell, the following code creates a resource group, injecting the current date and time into the resource group name.

`az resource create --name "rg-$(date +%d%m%y%H%M)" -location uksouth`

# References
Source: https://linuxsimply.com/bash-scripting-tutorial/string/basics/string-interpolation/