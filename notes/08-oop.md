* **Object oriented programming** is a paradigm where programs are organized into groups called **objects**.

#### Principles of OOP

* Robustness - effectively handles unexpected inputs
* Adaptability - can be run on different software and hardware
* Reusable - can be a subcomponent in other software
* Modularity - divided by functional units
* Abstraction - defined by methods rather than by implementation
* Encapsulation - interface can change without breaking other components

#### Class vs. Object

* Class contains the blueprint to instantiate an object, which acts out according to a class.
* Class namespaces hold data for the methods of the class across all instances whereas instance namespaces hold the data for a particular instance
* Class data can be instantiated outside a method but within the class to be particular to the entire class
* Can define `__slots` in the class to avoid storage of instance variables in a namespace dictionary. This is more memory efficient, but the verbosity and rigor is atypical for python and generally not necessary
