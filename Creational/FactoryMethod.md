Base Product, could be `interface` or `class`:

```cs
public interface IProduct {}
```

Concrete Products:

```cs
public class ConcreteProductA : IProduct {}

public class ConcreteProductB : IProduct {}
```

Creator class:

```cs
public abstract class Creator
{
	public abstract Product FactoryMethod();	
}
```

Concrete Creators:

```cs
public class ConcreteCreatorA : Creator
{
    public override IProduct FactoryMethod() => new ConcreteProductA();    
}

public class ConcreteCreatorB : Creator
{
    public override IProduct FactoryMethod() => new ConcreteProductB();    
}
```

Client:

```cs
var input = "a";

Creator creator;

if(input == "a") creator = new ConcreteCreatorA();
else if(input == "b") creator = new ConcreteCreatorB();
// ...

var product = creator.FactoryMethod();
// ...

```