#### Objects

* A statement like `x = 4` instantiates an **identifier** (e.g., `x`) that **points** to an **object** (e.g., `4`).
* A **class** is the "essence" of the object that explains how it works (e.g., an integer). An **object** is the instantiation of that class in a particular "form".
* Objects are **mutable** if they can be updated in place. **Immutable** objects cannot be updated, but the identifier could be re-assigned to a different object.

#### Methods

* Objects have **methods** that are defined as a part of the class. These are functions particular to an object.
* **Accessor methods** access or calculate data specific to the object without changing anything about the object.
* **Mutator methods** change something about the object.

#### Built-ins

| Class | Description | Default | Mutable? | Notes |
----------------------------------
| bool | Boolean (true or false) | `False` | No | |
| int | Integer (e.g., `1`) | `0` | No | Binary can be represented by, e.g., `0b011`, octal by, e.g., `0o52`, and hexidecimal by, e.g., `0x7f`. |
| float | Floating point number (e.g., `1.03`) | `0.0` | No | |
| str | character string | `""` | No | |
| list | sequence of objects | `[]` | Yes | The `list` constructor can be used on any iterable type (e.g., `list("hey")` makes `["h", "e", "y"]`. |
| tuple | immutable sequence of objects | `()` | No | A one-element tuple needs a trailing comma (e.g., `(1,)`) |
| set | ordered set of distinct objects | `set([])` | Yes | |
| frozenset | immutable form of set | `frozenset([])` No | |
| dict | associative key-value mapping | `{}` | Yes | |
