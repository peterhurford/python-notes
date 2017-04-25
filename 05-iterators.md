#### Iterables and Iterators

* An **iterable** is any object that can be iterated (e.g., through a `for` loop, such as strings, lists, dictionaries, and sets).
* An **iterator** is an object produced by the function `iter`. It will have a current value and a method called `next` that returns the next value or returns the `StopIteration` exception when there's no more elements.
* A `for` loop just automates the process of creating the iterator (calling `iter`) and calling `next`.
* A list iterator (result of calling `iter` on list) just stores an index to the list rather than a copy of the list, so if the original list is modified after the list iterator is made, the list iterator will return the updated values.
* `range` return a range object that is an iterator, this way the entire range does not need to be precalc or held all at once in memory. This is a lazy sequence where items are only calc when they are needed.


#### Generators

* A **generator** is a function that creates an iterator where each next value is given by the `yield` keyword.

```
def fib():
    a, b = 1, 1
    while True:
       yield a
       a, b = b, a+b
```
