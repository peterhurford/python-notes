| Operator | Meaning | Example | Notes |
| -------- | ------- | ------- | ----- |
| `not` | unary negation | `not True` -> `False` | |
| `and` | conditional and | `True and False` -> `False` | Short-circuits and stops calculating as soon as the first `False` is evaluated |
| `or` | conditional or | `True or False` -> `False` | Also short-circuits |
| `is` | same identity | `0.0 is 0` -> `False` | |
| `is not` | different identity | | |
| `=` | Assignment | | |
| `==` | equivalent | `0.0 == 0` -> `True` | |
| `!=` | not equivalent | | |
| `<` | Less than | | |
| `s < t` | Set `s` is a proper subset of set `t` | `set(1, 2) < set(1, 2, 3)` -> `True` | |
| `<=` | Less than or equal to | | |
| `s <= t` | Set `s` is a subset of set `t` | `set(1, 2, 3) <= set(1, 2, 3)` -> `True` | |
| `>` | Greater than | | |
| `s > t` | Set `s` is a proper superset of set `t` | | |
| `>=` | Greater than or equal to | | |
| `s >= t` | Set `s` is a superset of set `t` | | |
| `+` | Integer Addition | | |
| `x += n` | Add `n` to the value of `x` and reassign to `x` | | |
| `s + t` | Concatenate sequence `s` with sequence `t` | `[1, 2] + [3, 4]` -> `[1, 2, 3, 4]` | |
| `-` | Integer Subtraction | | |
| `s - t` | The elements in set `s` that are not in set `t` | | |
| `*` | Integer Multiplication | | |
| `**` | Integer Expoentiation | | |
| `k * s` | Repeat sequence `s` `k` times | `3 * [1, 2]` -> `[1, 2, 1, 2, 1, 2]` | |
| `/` | True division | `3 / 2` -> `1.5` | In Python2, `/` is also integer division. |
| `//` | Integer division | `3 // 2` -> `1` | |
| `%` | Modulus | `5 % 3` -> `2` | |
| `~` | Bitwise compliment (flips bits) | `~2` -> `~ 0000 0010` (in binary) -> `1111 1101` (flip bits) -> interpreted as `-3` by Python | In practice in Python, `~n` will always be `-(n+1)`.
| `&` | Bitwise and (logical and on each bit) | `5 & 3` -> `0101` and `0011` -> `0001` -> `1` | |
| `s & t` | Intersection of sets `s` and `t` | `{1, 2, 3, 4} & {3, 4, 5, 6}` -> `{3, 4}` | |
| `\|` | Bitwise or | `5 \| 3` -> `0101` or `0011` -> `0111` -> `7` | |
| `s \| t` | Union of sets `s` and `t` | `{1, 2, 3} | {3, 4, 5}` -> `{1, 2, 3, 4, 5}` | |
| `^` | Bitwise exlcusive or | `5 ^ 3` -> `0101` xor `0011` -> `0110` -> `6` | |
| `s ^ t` | The elements that are in precisely one but not both of sets `s` and `t` | `{1, 2, 3, 4} ^ {3, 4, 5, 6}` -> `{1, 2, 5, 6}` | |
| `<<` | Shift bits left | `5 << 1` -> `0101 << 1` -> `1010` -> `10` | |
| `>>` | Shift bits right | `5 >> 1` -> `0101 >> 1` -> `0010` -> `2` | |
| `s[j]` | Element of `s` and index `j` | `[1, 2, 3][2]` -> `3` | Python array indices start at 0 |
| `s[q:p]` | Elements of `s` from index `q` to index `p-1` | `[1, 2, 3, 4][1:3]` -> `[2, 3]` | |
| `s[q:p:n]` | Every `n`th element of `s`, starting from index `q`, up to (but not including) `p`` | `[1, 2, 3, 4, 5, 6][1:5:2]` -> `[2, 4]` | |
| `k in s` | Check if element `k` is in `s` | `1 in [1, 2, 3]` -> `True` | |
| `k not in s` | Check if element `k` is not in `s` | `1 not in [1, 2, 3]` -> `False` | |
