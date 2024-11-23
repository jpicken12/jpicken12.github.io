2024-08-16 22:12

Status:

Tags: #LearnPowerShell/Chapter9 #PowerShell/ParameterBinding 

# Pwsh parameter binding
- There are 2 methods; 
	- pwsh will first try [[byValue]] 
	- if that doesn't work it will try [[byPropertyName]]
- byPropertyName is great when properties line up with parameters, but when they do not, [custom properties](https://read.amazon.com/?asin=B097814LF4&ref_=kwl_kr_iv_rec_1) can be used to dynamically change the input to what you need 
- When you still can't get parameter binding to work, consider [parenthetical commands](https://read.amazon.com/?asin=B097814LF4&ref_=kwl_kr_iv_rec_1) This is a trick that doesn't rely on pipeline parameter binding
	- This is where a command you want to run first is placed inside () then it's output is fed to another commands parameter i.e.
	- ```Get-WMIObject -class Win32_BIOS -computerName (Get-Content .\computers.txt)```
	- This produces values of type string and feeds them to -computerName parameter
- Another trick is to use select-object -expand to [extract the value from a single property](https://read.amazon.com/?asin=B097814LF4&ref_=kwl_kr_iv_rec_1) This is useful when command types between 2 objects do not match.


# References
Source: [Parameter Binding](https://read.amazon.com/?asin=B097814LF4&ref_=kwl_kr_iv_rec_1) 
[[LWPWSH Chapter 9]]