# Hello World

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

