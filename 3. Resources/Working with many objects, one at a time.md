2024-09-09 22:28

Status:

Tags: #PowerShell/Chapter16 

# Working with many objects, one at a time

- Many Pwsh cmdlets can accept batches, or collections, of objects to work with i.e. Get-Service | Stop-Service. This is an example of batch administration and results in less complex syntax.
- Another option is to use Get-WMIObject. If you can get an object using that cmdlet, then Invoke-WMIObject can execute its methods
- Another option is to enumerate the objects one at a time and execute a method on each of them.
- Note, you can never pipe anything to a method. Only from one cmdlet to another.

# References
Source: [Chapter 16. Working with many objects, one at a time](https://read.amazon.co.uk/?asin=B097814LF4&ref_=kwl_kr_iv_rec_1) 
[[Learn Windows PowerShell]]