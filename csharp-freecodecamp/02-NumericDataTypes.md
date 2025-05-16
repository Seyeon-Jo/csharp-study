# 02-Numeric Data Types

<br>

## Numeric Data Types Table

| Type | Use For | Example |
| :--- | :------ | :------ |
| int | whole numbers | int x = 10; |
| double | decimals (default) | double d = 3.14; |
| float | decimals (less precise) | float f = 3.14f; |
| decimal | money values | decimal m = 9.99m; |
| long | big whole numbers | long l = 12345678900; |
| short | small whole numbers | short s = 100; |

### 1. `int`
- 용도: 소수점 없는 정수 (whole numbers)
- 범위: –2,147,483,648 to 2,147,483,647  
- 예시:
```csharp
  int age = 25;
````

### 2. `double`
- 용도: 소수점 있는 숫자 (decimals), 정밀도 높음
- 예시:
```csharp
double price = 19.99;
```

### 3. `float`
- 용도: 소수점 있는 숫자 (decimals), double보다 덜 정밀
- 주의: 숫자 뒤에 `f` 붙이기
- 예시:
```csharp
float temperature = 36.6f;
```

### 4. `decimal`
- 용도: 돈 계산 등 고정밀 숫자에 사용
- 주의: 숫자 뒤에 `m` 붙이기
- 예시:
```csharp
decimal salary = 4500.75m;
```

### 5. `long`
- 용도: int보다 큰 정수
- 범위: –9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
- 예시:
```csharp
long population = 8000000000;
```

### 6. `short`
- 용도: 작은 정수
- 범위: –32,768 to 32,767
- 예시:
```csharp
short students = 1200;
```

<br> 

## Declaring and Initializing
