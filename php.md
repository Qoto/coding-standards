Naming standards:
=================
Classes: `PascalCase`

Methods, Properties, Functions, Variables: `camelCase`

Constants: Upper case with underscore: `CONST_EXAMPLE`
 
Variable that holds a model object should have the name of the model class, example:

`$customer = new Customer(‘x’);`

Variable that don’t hold models (int/bool/str) should be named with a meaningful name: `$customerId`, `$customerIdsArr`
 
Arrays:

Array with keys and values: `array(‘x’=>’1’,’y’=>’2’);`
Array with only values: `array(‘1’,’2’);`
 
Blocks of code:

All blocks should be closed with `{ }` even if it’s an IF statement with 1 statement line.
 
Brackets:
Always on separate line, example:

```
If(true)
{
 //…
}
```
 
Comments:
Add function description like so:
```
/**
* description
*/
```
 
One line comment with `//` not `/*..*/`
 
Function length: 

functions with +70 lines should be broken into multiple functions if possible, for ease of readability, maintanence and code reuseability.
