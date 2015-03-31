
1. Files
--------

- Files MUST use only `<?php` tags only.

- Files MUST use only UTF-8 without BOM for PHP code.

- Files SHOULD *either* declare symbols (classes, functions, constants, etc.)
  *or* cause side-effects (e.g. generate output, change .ini settings, etc.)
  but SHOULD NOT do both.

- All files MUST use the Unix LF (linefeed) line ending.

- All files MUST end with a single blank line.

- The closing ?> tag MUST be omitted from files containing only PHP.


2. Naming standards
-------------------
__namespaces:__  `namespace Vendor\Model;`
__Classes:__ `StudlyCaps`

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
