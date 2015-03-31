Naming standards:
=================
__Classes:__ `PascalCase`

__Methods, Properties, Functions, Variables:__ `camelCase`

__Constants:__ Upper case with underscore: `CONST_EXAMPLE`

__Variables:__

Variable that holds a model object should have the name of the model class

Example: `$customer = new Customer(‘x’);`

Variable that don’t hold models (int/bool/str) should be named with a meaningful name:

Example: `$customerId`, `$customerIdsArr`
 
__Arrays:__

Array with keys and values: `array(‘x’=>’1’,’y’=>’2’);`
Array with only values: `array(‘1’,’2’);`
 
__Blocks of code:__

All blocks should be closed with `{ }` even if it’s an IF statement with 1 statement line.
 
__Brackets:__

Always on separate line

Example:

```
If(true)
{
 //…
}
```
 
__Comments:__

Add function description like so:
```
/**
* description
*/
```

One line comment with `//` not `/*..*/`
 
__Function length: __

functions with +70 lines should be broken into multiple functions if possible, for ease of readability, maintanence and code reuseability.
