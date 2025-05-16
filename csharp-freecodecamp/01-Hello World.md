# Hello World

<br>

## Why do both work?

```csharp
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");
    }
  }
}
```

I am using `using System;`, which lets me write just `Console.WriteLine` without needing to write `System.Console.WriteLine`.

```csharp
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      System.Console.WriteLine("Hello World!");
    }
  }
}
```

I am not using `using System;`, but instead I am writing the full name: `System.Console.WriteLine`.

So, why do both work?

Because:
- `Console` is part of the `System` namespace.
- If I write `using System;`, I can just say `Console.WriteLine(...)`
- If I don't use `using System;`, I need to write the full name: `System.Console.WriteLine(...)`

Think of it like this:

Imagine you live in a house (`System`) and you want to use a toaster (`Console.WriteLine()`):
- If you are already inside the house (`using System;`), you can just say "use the toaster."
- If you are outside the house, you need to say "go to the house and use the toaster" (`System.Console.WriteLine`).
