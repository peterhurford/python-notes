| Operator | Meaning | Object | Example | Notes |
| -------- | ------- | ------ | ------- | ----- |
| `not` | unary negation | | `not True` -> `False` | |
| `and` | conditional and | | `True and False` -> `False` | Short-circuits and stops calculating as soon as the first `False` is evaluated |
| `or` | conditional or | | `True or False` -> `False` | Also short-circuits |
| `is` | same identity | | `0.0 is 0` -> `False` | |
| `is not` | | different identity | | |
| `=` | Assignment | | | |
| `==` | equivalent | `__eq__` | `0.0 == 0` -> `True` | |
| `!=` | not equivalent | `__ne__` | | |
| `<` | Less than | `__lt__` | | |
| `s < t` | Set `s` is a proper subset of set `t` | | `set(1, 2) < set(1, 2, 3)` -> `True` | |
| `<=` | Less than or equal to | `__le__` | | |
| `s <= t` | Set `s` is a subset of set `t` | | `set(1, 2, 3) <= set(1, 2, 3)` -> `True` | |
| `>` | Greater than | `__gt__` | | |
| `s > t` | Set `s` is a proper superset of set `t` | | | |
| `>=` | Greater than or equal to | `__ge__` | | |
| `s >= t` | Set `s` is a superset of set `t` | | | |
| `+` | Integer Addition | `__add__` | | |
| `x += n` | Add `n` to the value of `x` and reassign to `x` | `__iadd__` | | |
| `s + t` | Concatenate sequence `s` with sequence `t` | | `[1, 2] + [3, 4]` -> `[1, 2, 3, 4]` | |
| `-` | Integer Subtraction | `__sub__` | | |
| `s - t` | The elements in set `s` that are not in set `t` | | | |
| `*` | Integer Multiplication | `__mul__` | | |
| `**` | Integer Expoentiation | `__pow__` | | |
| `k * s` | Repeat sequence `s` `k` times | | `3 * [1, 2]` -> `[1, 2, 1, 2, 1, 2]` | |
| `/` | True division | `__truediv__` | `3 / 2` -> `1.5` | In Python2, `/` is also integer division. |
| `//` | Integer division | `__floordiv__` | `3 // 2` -> `1` | |
| `%` | Modulus | `__mod__` | `5 % 3` -> `2` | |
| `~` | Bitwise compliment (flips bits) | `__invert__` | `~2` -> `~ 0000 0010` (in binary) -> `1111 1101` (flip bits) -> interpreted as `-3` by Python | In practice in Python, `~n` will always be `-(n+1)`.
| `&` | Bitwise and (logical and on each bit) | `__and__` | `5 & 3` -> `0101` and `0011` -> `0001` -> `1` | |
| `s & t` | Intersection of sets `s` and `t` | | `{1, 2, 3, 4} & {3, 4, 5, 6}` -> `{3, 4}` | |
| `\|` | Bitwise or | `__or__` | `5 \| 3` -> `0101` or `0011` -> `0111` -> `7` | |
| `s \| t` | Union of sets `s` and `t` | | `{1, 2, 3} | {3, 4, 5}` -> `{1, 2, 3, 4, 5}` | |
| `^` | Bitwise exlcusive or | `__xor__` | `5 ^ 3` -> `0101` xor `0011` -> `0110` -> `6` | |
| `s ^ t` | The elements that are in precisely one but not both of sets `s` and `t` | | `{1, 2, 3, 4} ^ {3, 4, 5, 6}` -> `{1, 2, 5, 6}` | |
| `<<` | Shift bits left | `__lshift__` | `5 << 1` -> `0101 << 1` -> `1010` -> `10` | |
| `>>` | Shift bits right | `__rshift__` | `5 >> 1` -> `0101 >> 1` -> `0010` -> `2` | |
| `s[j]` | `__getitem__` | Element of `s` and index `j` | `[1, 2, 3][2]` -> `3` | Python array indices start at 0 |
| `s[q:p]` | | Elements of `s` from index `q` to index `p-1` | `[1, 2, 3, 4][1:3]` -> `[2, 3]` | |
| `s[q:p:n]` | | Every `n`th element of `s`, starting from index `q`, up to (but not including) `p`` | `[1, 2, 3, 4, 5, 6][1:5:2]` -> `[2, 4]` | |
| `k in s` | `__contains__` | Check if element `k` is in `s` | `1 in [1, 2, 3]` -> `True` | |
| `k not in s` | | Check if element `k` is not in `s` | `1 not in [1, 2, 3]` -> `False` | |
