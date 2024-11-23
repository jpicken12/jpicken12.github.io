2024-07-29 17:27

Status:

Tags: #JMESPath

# JMESPath

I created a PowerShell script which uses azure CLI and JMESPath queries to return certain information about a virtual machine and it's disks. This was tricky (for me) because I was using 2 Azure CLI commands (az vm show and az vm list-sizes) and attempting to add the output to a PS Custon Object.

In so doing I learned some important points about JMESPath:

- Literals must be surrounded by back ticks
- Must surround strings with ''
- [] operator flattens an array
- An array can be flattened at multiple layers of the output, not just at the to-level result returned
- There are operators that can be used to filter an array can also use boolean expressions
- The terms dictionary and object are used interchangeably

# References
Source: 
[[JMESPath]]