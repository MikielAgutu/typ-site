# Types, variables, and values

C# is a strongly-typed language. Every variable and constant has a type, as does every expression that evaluates to a value. Every method signature specifies a type for each input parameter and for the return value.

Here's an example of some C# code:

 ```c#
int a = 5;
int b = a + 2; //OK

bool test = true;

// Error. Operator '+' cannot be applied to operands of type 'int' and 'bool'.
int c = a + test;
 ```

Try and run it in your favorite IDE.

![csharp-logo](./csharp-logo.png)