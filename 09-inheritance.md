#### Inheritance

* Inheritance is used to specialize a class by providing new methods or by overriding existing methods
* child class / sub class **inherits** from base class / patent class / super class 
* A child class has all methods of parent class by default
* An **abstract base class** is class only used for inheritance that doesn't make sense to use on its own
* `@abstractmethod` decorator on a method in an abstract base class allows you to define the method without implementing it and then any class that inherits from your ABC must override the abstract method or python will declare it invalid
