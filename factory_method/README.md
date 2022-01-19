## Factory Method ##

Facilitates the creation of other objects.

### Participants

* Product: defines the interface of objects the factory method creates.
* ConcreteProduct: implements the Product interface.
* Creator: 1. declares the factory method, which returns an object of type Product. Creator may also define a default implementation of the factory method that returns a default ConcreteProduct object; 2. may call the factory method to create a Product object;
* ConcreteCreator:overrides the factory method to return an instance of a ConcreteProduct.