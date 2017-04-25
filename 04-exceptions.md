* Errors in Python are called **exceptions** and are **raised** with the function `raise`.

**Built-in Python Exceptions**

| Class | Description |
| ----- | ----------- |
| Exception | A base class for most error types |
| AttributeError | Raised by syntax `obj.foo`, if `obj` has no member named `foo`. |
| EOFError | Raised if "end of file" reached for console or file input |
| IOError | Raised upon failure of I/O operation (e.g., opening file) |
| IndexError | Raised if index to sequence is out of bounds |
| KeyError | Raised if nonexistent key requested for set or dictionary |
| KeyboardInterrupt | Raised if user types `Ctrl-C` while program is executing | 
| NameError | Raised if nonexistent identifier used |
| StopIteration | Raised by `next(iterator)` if no element |
| TypeError | Raised when wrong type of parameter is sent to a function |
| ValueError | Raised when parameter has invalid value (e.g., `sqrt(−5)`) |
| ZeroDivisionError | Raised when any division operator used with 0 as divisor |

* It is customary to check the type of parameters (raising a `TypeError`) before checking the values of parameters (raising a `ValueError`).
* Because Python is a dynamic language and raises errors well by default, generally a lot of Python functions do not check types or values that often.
