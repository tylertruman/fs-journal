# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
To declare a scope that contains a set of related objects. (To organize and provide separation)
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes are reference types, whereas structs are value types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Using ref in your method's parameter.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
Reference Type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It cannot be used to create objects and to access it, it must be inherited from another class.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
To allow it to be overridden.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, and internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only within the body of the class or struct in which they are declared.
```