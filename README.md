# Singleton Design Pattern – C#

This project demonstrates the **Singleton Design Pattern** implemented in C#.

## What is the Singleton Pattern?
The Singleton Pattern ensures that a class has **only one instance** and provides a global access point to it.
 
## Implementation Details
- Private constructor to prevent direct instantiation
- Static instance variable
- Thread-safe lazy initialization using `lock`

## Example Usage
```csharp
Singleton s1 = Singleton.GetInstance();
Singleton s2 = Singleton.GetInstance();
Console.WriteLine(s1 == s2); // True
```

## Output
True

## Concepts Demonstrated
- Singleton Design Pattern
- Thread safety
- Encapsulation
- Lazy initialization

## Technologies
- C#
- Console Application
- Visual Studio
