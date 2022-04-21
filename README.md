# Skeedge#

Skeedge# (pronounced *Skeedge Sharp*) is a compiled programming language written in Python.
It has fairly simple syntax and is similar to Basic/Visual Basic. Skeedge# transpiles to C.

Here's some example code:
```
Module {
    # Comments!

    Label Begin; # Labels

    PrintLn("Hello, world!");
    Var myVar = 10; # No type hinting, yay!
    InputNum myInputVar; # Get input from stdin

    # While loops
    While myVar > 0 {
        PrintLn(myVar);
        Var myVar = myVar - 1;
    };

    # If statements
    If myInputVar == 2 {
        PrintLn("You entered two!");
    };

    GoTo Begin; # Go back to the Begin label
};
```