# 02-Numeric Data Types

<br>

## Number Data Types Overview

This explains the most commonly used number data types in C#.

### 1. `int`
- Purpose: Whole numbers (no decimal points)
- Range: –2,147,483,648 to 2,147,483,647  
- Example:
```csharp
int age = 25;
````

### 2. `double`
- Purpose: Decimal numbers with high precision
- Example:
```csharp
double price = 19.99;
```

### 3. `float`
- Purpose: Decimal numbers with lower precision than `double`
- Note: Add `f` at the end of the number
- Example:
```csharp
float temperature = 36.6f;
```

### 4. `decimal`
- Purpose: Used for money or high-precision decimal values
- Note: Add `m` at the end of the number
- Example:
```csharp
decimal salary = 4500.75m;
```

### 5. `long`
- Purpose: Whole numbers larger than `int`
- Range: –9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
- Example:
```csharp
long population = 8000000000;
```

### 6. `short`
- Purpose: Small whole numbers
- Range: –32,768 to 32,767
- Example:
```csharp
short students = 1200;
```

### Quick Comparison Table

| Type      | Description                      | Range/Note                      | Example                         |
| --------- | -------------------------------- | ------------------------------- | ------------------------------- |
| `int`     | Whole numbers                    | –2,147,483,648 to 2,147,483,647 | `int age = 25;`                 |
| `double`  | Decimal numbers (high precision) | Default type for decimals       | `double price = 19.99;`         |
| `float`   | Decimal numbers (less precise)   | Add `f` at the end              | `float temp = 36.6f;`           |
| `decimal` | Money values, high precision     | Add `m` at the end              | `decimal salary = 4500.75m;`    |
| `long`    | Large whole numbers              | Larger range than `int`         | `long population = 8000000000;` |
| `short`   | Small whole numbers              | –32,768 to 32,767               | `short students = 1200;`        |

<br> 

## Declaring and Initializing

Initializing and declaring in the same line:
```csharp
int age = 23; // Initializing and declaring in the same line

Console.WriteLine(age); // print out age '23'
```

Initializing and declaring separately:
```csharp
int age; // declare in the first line
age = 23; // give it an initial value in the second line
```

