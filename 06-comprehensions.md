| Name | Example |
| ---- | ------- |
| List comprehension | `[x for x in xs]` |
| Set comprehension | `{x for x in xs}` |
| Dict comprehension | `{k: v for k, v in kvs}` |
| Generator comprehension | `(x for x in range(10))` |

Can call `sum` on generator comprehension, e.g., `sum(x + 3 for x in xs)`, as a faster way to sum.
