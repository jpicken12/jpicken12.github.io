2024-07-31 14:02

Status:

Tags: #PowerShell 

# Working with the PowerShell pipeline

A pipeline takes the output from one cmdlet and uses it as the input to the next. i.e.
```
Get-Process | Sort-Object Id
```
or;
```
Get-Process Notepad | Stop-Process
```

An important concept in PowerShell is the automatic variable *$PSItem*. This contains the current object in the pipeline and is commonly seen written in its shorthand form $_ 

You can change the display output of data by piping to *Format-List* or *Format-Table*, for example. The former will show the complete list of properties of an object.

Piping into *Select-Object* means you can specify the properties of the object to return.

*Where-Object* is very similar to Select-Object but we can provide criteria. 
# References
Source: [Working with PowerShell pipeline](https://www.youtube.com/watch?v=QKmyf6c83Rs&list=PL2j0_s2VJe2hzQuQyn6yfMS2olhhs4UnQ&index=3) 
[[Learn PowerShell]] 