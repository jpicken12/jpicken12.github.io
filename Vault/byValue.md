2024-09-02 14:39

Status:

Tags: #PowerShell/ParameterBinding #LearnPowerShell/Chapter9 

# byValue
- Pwsh will look at the type of object produced by commandA and see if any paramters of commandB can accept that type of object from the pipeline
- Get-Command commandA would tell you the type of object it produces i.e. string
- The help of commandB will tell you if any of the parameters 'Accept pipeline input' and it will tell you the type of that parameter i.e. \<string\[\]\> 
- Those types need to match
- Pwsh permits only one parameter to accept a given type of object from the pipeline byValue
- 


# References
Source: [[Pwsh parameter binding]]