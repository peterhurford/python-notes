* Assignments to variables are made within specific **namespaces**. This process is called **scoping**.
* The highest-level namespace is the **global namespace** and variables here have **global scope**. They can be accessed from anywhere.
* Executions within a function have **local scope** and can only be accessed within that function.
* Namespaces are implemented as Python dictionaries.
* `dir` lists the names of all variables in the current namespace. `vars` lists the dictionary of names and values.
