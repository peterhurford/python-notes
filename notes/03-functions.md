* A **function** is a free-standing object, not associated with any other object, that takes input **parameters** and returns an **output**.
* Parameters can be passed to a function **by reference**, where the memory location associated with the parameter is passed directly, or **by copy**, where a copy of the object is made for the function.
* In passing by reference, a function can update the object if the object is mutable, which may have unintentional side-effects. It is, however, more efficient and faster than passing by copy, since a copy does not need ot be made.
* Python does pass by reference.
* **Polymorphic** functions do different things when given different inputs (e.g., `+` performs differently with numbers and lists).
* Python functions can be called with different arities if a function has **default parameters**, which is the value the parameter takes if it is not passed.
