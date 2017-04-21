| Operator | Meaning | Example | Notes |
| -------- | ------- | ------- | ----- |
| `not` | unary negation | `not True` -> `False` | |
| `and` | conditional and | `True and False` -> `False` | Short-circuits and stops calculating as soon as the first `False` is evaluated |
| `or` | conditional or | `True or False` -> `False` | Also short-circuits |
| `is` | same identity | `0.0 is 0` -> `False` | |
| `is not` | different identity | | |
| `==` | equivalent | `0.0 == 0` -> `True` | |
| `!=` | not equivalent | | |
| `<` | Less than | | |
| `<=` | Less than or equal to | | |
| `>` | Greater than | | |
| `>=` | Greater than or equal to | | |
| `+` | Addition | | |
| `-` | Subtraction | | |
| `*` | Multiplication | | |
| `/` | True division | `3 / 2` -> `1.5` | In Python2, `/` is also integer division. |
| `//` | Integer division | `3 // 2` -> `1` | |
| `%` | Modulus | `5 % 3` -> `2` | |
| `~` | Bitwise compliment (flips bits) | `~2` -> `~ 0000 0010` (in binary) -> `1111 1101` (flip bits) -> interpreted as `-3` by Python | In practice in Python, `~n` will always be `-(n+1)`.
| `&` | Bitwise and (logical and on each bit) | `5 & 3` -> `0101` and `0011` -> `0001` -> `1` | |
| `|` | Bitwise or | `5 | 3` -> `0101` or `0011` -> `0111` -> `7` | |
| `^` | Bitwise exlcusive or | `5 ^ 3` -> `0101` xor `0011` -> `0110` -> `6` | |
| `<<` | Shift bits left | `5 << 1` -> `0101 << 1` -> `1010` -> `10` | |
| `>>` | Shift bits right | `5 >> 1` -> `0101 >> 1` -> `0010` -> `2` | |
