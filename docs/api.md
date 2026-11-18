# API 参考

`add(a, b)` 返回 `a + b`。例如 `add(-1, 1)` 返回整数 `0`。

`multiply(a, b)` 返回 `a * b`。例如 `multiply(3, 4)` 返回整数 `12`。

```python
from calculator import add, multiply

print(add(2, 3))       # 5
print(multiply(2, 0))  # 0
```

参数使用支持相应运算符的数值，返回值遵从 Python 的数值运算规则。
