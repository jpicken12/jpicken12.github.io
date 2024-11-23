2024-07-31 13:50

Status:

Tags: #PowerShell 

# Learn and use PowerShell with just 3 commands

- PowerShell works in objects
- Cmdlets are named using verb-noun, as seen below
- Modules are a collection of cmdlets

## Get-Command
- Lists commands that are available on a device
- Can use wild cards i.e.
```
- Get-Command \*process\*
```

## Get-Member
- Can help you find other properties by evaluating a cmdlet
- Tells you the type of object such as Int32 for Get-Random

## Get-Help
Get help gives you help information about a command, bit like man on Linux. There is a -Example parameter that will output some example use cases of the command.

# Bonus
## Find-Module
Use -tag to search the PowerShell gallery to see if there is a module with the capability you want. i.e.
```
Find-Module -tag telegram
```

# References
Source: https://www.youtube.com/watch?v=cDcS6iL1G4I&list=PL2j0_s2VJe2hzQuQyn6yfMS2olhhs4UnQ&index=2&pp=iAQB
[[Learn PowerShell]] 