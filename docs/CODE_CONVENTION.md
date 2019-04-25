## Summary
This page has several rules when contribute codes to this repository.

## Language Standard
In **Project Philosopher's Stone**, contributors who codes with C++ should comply the lastest standard unless its cost overs to code with previous one.

 * Use **module** instead of **header**.

## Naming
Every variables, functions, classes, macros, and namespaces must be named in clear, easy to understand. **snake notation** is used for C++ codes in this repository.
For example, If there were some spaces in the name, replace with _(underscore). Every characters must be typed in small letter like this: `flag`, `file_ptr` however, SNAKE(not snake) notation is required for macros like this: `VGA_ADDRESS`, `SYSTEM_PREFIX`

Please, do not use [Hungarian notation](https://en.wikipedia.org/wiki/Hungarian_notation) on code, except these cases:
 * private member of classes or structures : `m_some_name`
 * static member of classes or structures  : `s_some_name`
 
We do not recommend to use underscore as the first or the last character of the name: `_name` or `name_`

## Indentations
4-Spaces Indent is recommended. Before you commit your code, please check the indentation settings of your editor/IDE.

## Brackets
Allman style alignment is required for the brackets. Google or K&R Style is not allowed.
