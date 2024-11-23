2024-07-26 13:38

Status:

Tags: #Azure-CLI/Output 

# Azure CLI Output

[[Azure Command Line Interface]] uses JSON as it's default output. The --output parameter can be used to alter the default output. The following options are available:

| --output | Description                                |
| -------- | ------------------------------------------ |
| json     | JSON string. Default                       |
| jsonc    | Colonised json                             |
| table    | ASCII table with keys as column headings   |
| tsv      | Tab-separated values, with no keys         |
| yaml     | YAML, a human readable alternative to json |
| yamlc    | Colonized yaml                             |
| none     | No output other than errors and warnings   |
## Table

Some fields, and nested objects, aren't included in table output (but can still be filtered on). Use table when you need a simple overview.

## Tab Separated Values

TSV also does not include nested objects, and there is no guarantee of the output order. As such, the multiselect list feature of [[Azure CLI -query]] parameter is needed.

# References
Source: https://learn.microsoft.com/en-us/cli/azure/what-is-azure-cli#output-formats

Output formats: https://learn.microsoft.com/en-us/cli/azure/format-output-azure-cli?tabs=bash