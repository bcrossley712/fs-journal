# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
The namespace is directly related to the file name and shows the path for each space which that file works in. When using other files you can "using" other namespaces.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Classes are the only ones we've used that I know of. They are a reference type where as struct are value types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
void
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
I don't believe we have gone over abstract. Meant to be used as a base layer and not instanciated on it's own.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Not sure but the net says that it allows the class to be overridden.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, internal, protected.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only methods within it's own namespace.
```