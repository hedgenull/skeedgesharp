# Skeedge#: A small but functional programming language

Skeedge# (pronounced *Skeedge Sharp*) is a compiled programming language written in Python.
It has fairly simple syntax and is similar to Basic/Visual Basic but with some C/Java elements.
Skeedge# transpiles to Python code.

Here's some example code (the syntax is close to PHP's so that's what the highlighting is):
```php
# All code must be included in a 'Module'.
Module {
    # Single-line comments use the hash mark.
    ~ Multi-line comments use
      the tilde symbol. ~

    PrintLn("Hello, world!");
    $myVar = 10; # No type hinting
    InputNum $myInputVar; # Get input from stdin

    # While loops
    While $myVar > 0 {
    PrintLn($myVar); # Indentation isn't needed anywhere, but it looks nicer.
    $myVar = $myVar - 1;
    };

    # If statements
    If $myInputVar < 2 {
        PrintLn("That's less than two!");
    };
};
```