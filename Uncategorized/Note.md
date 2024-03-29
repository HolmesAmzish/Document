## 表达式

1. **中缀表达式**：这是我们通常使用的表达式形式，例如 `2 + 3 * 4`。在中缀表达式中，运算符位于操作数的中间。但是，中缀表达式需要遵循运算符的优先级和括号的规则来确保正确的计算顺序。
2. **前缀表达式**（也称为波兰前缀表达式）：在前缀表达式中，运算符位于操作数的前面。例如，上述中缀表达式的前缀形式为 `+ 2 * 3 4`。
3. **后缀表达式**（也称为逆波兰后缀表达式）：在后缀表达式中，运算符位于操作数的后面。例如，上述中缀表达式的后缀形式为 `2 3 4 * +`。

在计算前缀和后缀表达式时，不需要考虑运算符的优先级或者括号，因为表达式中的运算顺序已经由运算符的位置确定了。这种特性使得计算机更容易处理这些表达式，而无需解析和理解运算符的优先级和括号。