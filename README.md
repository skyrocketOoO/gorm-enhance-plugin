# gorm-enhance-plugin
The purpose of this module is to enhance the gorm on each aspect without influent origin method to make sure flexibility.

## Considerations of Gorm
- Need to use SELECT(colume) which is also exist on output 
- Hard code column name and operator
- .Table will use hard code table name but .Model need to initialize the model which may influent performance

## Target
- Gen column definiton code which avoid hard code
- Define Operator to avoid hard code
- Auto add .Select from output
- 

## TODO
- Parse column with various case
- Output address customize
- Generate same structure(only set scalar type to interface{}) for where condition 
https://wiki.goframe.org/pages/viewpage.action?pageId=7296196