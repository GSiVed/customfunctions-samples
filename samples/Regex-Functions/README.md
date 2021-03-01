# Geetha Sivasailam's UDF Library
Functions that performs regex match on currency, percent & time formats
* [RegexUtils](https://github.com/pnp/customfunctions-samples/tree/main/samples/Regex-Functions#Regex-Utils)
</br></br>

# Regex Utils
Functions that perform operations on a date value
* [IsCurrency](https://github.com/pnp/customfunctions-samples/tree/main/samples/Regex-Functions#IsCurrency)
* [IsPercent](https://github.com/pnp/customfunctions-samples/tree/main/samples/Regex-Functions#IsPercent)
* [IsTime](https://github.com/pnp/customfunctions-samples/tree/main/samples/Regex-Functions#IsTime)
</br></br>

## IsCurrency
Regex to validate currency format (US)
### Syntax
IsCurrency(CurrencyTxt)
* CurrencyTxt: Required
### Output
* Boolean
</br></br>


## IsPercent
Regex to validate percent format
### Syntax
IsPercent(PercentTxt)
* PercentTxt: Required
### Output
* Boolean
</br></br>


## IsTime
Regex to validate time format [hh:mm:ss]/[hr:min:sec]/[mm:ss]/[m:s]/[ss]/[s]
### Syntax
IsTime(TimeTxt)
* TimeTxt: Required
### Output
* Boolean
</br></br>
