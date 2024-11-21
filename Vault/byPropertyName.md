2024-09-02 14:56

Status:

Tags: #PowerShell/ParameterBinding #LearnPowerShell/Chapter9 

# byPropertyName

- Pwsh compares the properties of commandA to the parameters of commandB, if they match (and accept pipeline input is true) then this will work
- i.e. you can pipe import-csv to new-alias where name and value are properties of import-csv and also parameters (that accept pipeline input byPropertyName) of new-alias

# References
Source: [Parameter Binding byPropertyName](https://read.amazon.com/?asin=B097814LF4&ref_=kwl_kr_iv_rec_1) 
[[Pwsh parameter binding]]