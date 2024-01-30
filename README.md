Basic C# program that prints "Hello, World!" to the console:

```csharp
using System;

namespace HelloWorld {
    class Program {
        static void Main(string[] args) {
            Console.WriteLine("Hello, World!");
        }
    }
}
```

Explanation:

- We begin by importing the `System` namespace which contains the `Console` class that we'll use for output.
- Next, we define a namespace called `HelloWorld`.
- Inside this namespace, we define a class called `Program`.
- Within the `Program` class, we have a `Main` method. This is the entry point of our program.
- Inside the `Main` method, we use `Console.WriteLine` to output the text "Hello, World!" to the console.
- Finally, the program execution ends.

To run this program, you would need to compile it using a C# compiler (like `csc` on Windows) and then execute the resulting executable file. Alternatively, you can use an integrated development environment (IDE) like Visual Studio or Visual Studio Code to write, compile, and run the program.
