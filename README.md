# MiniC Compiler (ANTLR)

This compiler generates the syntax tree for MiniC inputs. It implements MiniC parts (ex. if-else, while and break structuresas well as functions), mathematical and logical operations. Furthermore, the program supports the storaging of variables with identifier (e.g. var = 1 where var is the name of the variable and 1 is its value). The operations between the numbers/variables that are supported are (with C# symbolism): +, -, *, /, %, ++, -, &&, ||, !, >, >=, ==, <, <=, !=, &, |, ~, ^, << and >>.

To run this solution/project, you would need Visual Studio 2017 (and install the ANTLR packages there) and Graphviz.

The input.txt file in the \bin\Debug\ folder is the MiniC input commands that the compiler will process (i.e. the MiniC expressions mentioned earlier)
and the input.c file in the \Testbench\ folder is the compilable C code that is produced.
