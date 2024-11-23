2024-08-03 14:51

Status:

Tags: #PowerShell #PowerShell/Variables #PowerShell/Quotes

# Working with PowerShell Variables

- PowerShell is not a strong typed language, meaning variables have the potential to be any data type.
- You can front load variables to enforce the data type, i.e.
  ```[int]$num = '2'``` will force PowerShell to load integer values, even though single quotes were used.
- Variables can be converted to other types i.e. ```iAmAStringNow = $num.toString()``` 
- toString() is a method. Get-Member is used to find the methods available.
- Single quotes will always result in a literal string
- Double quotes will still result in a string but is capable of working with dynamic components within that string.
- Get-Variable will list the constant(reserved) variables.
- Get-ChildItem env; will list environment variables

## Example
```
$path = Read-Host -Prompt 'Please enter the filepath you wish to scan for large files...'
$rawFileData = Get-ChildItem -Path $path -recurse
$largeFiles = $rawFileData | Where-Object {$.length -gt 100MB}
$largeFilesCount = $largeFiles | Measure-Object | Select-Object -ExpandProperty Count
Write-Host "You have $largeFilesCount large file(s) in $path"
```



# References
Source: 