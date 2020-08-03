Base Product, could be `interface` or `class`:

```cs
public interface IProduct {}
```

Concrete Products:

```cs
public class ConcreteProductA : IProduct {}

public class ConcreteProductB : IProduct {}
```

Creator/Factory:

```cs
public class Creator
{
    public IProduct GetProduct(string input) 
    {
        if(input == "a") return new ConcreteProductA();
        else if(input == "b") return new ConcreteProductB();

        // ...
    }
}
```

Client:

```cs
var input = "a";
var creator = new Creator();
var product = creator.GetProduct(input);
// ...
```