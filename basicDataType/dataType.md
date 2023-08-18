一、Number 类型
let n = 123; n = 12.345;

number 类型代表整数和浮点数。

数字可以有很多操作，比如，乘法 *、除法 /、加法 +、减法 - 等等。



二、BigInt 类型
在 JavaScript 中，“number” 类型无法表示大于 (253-1)（即 9007199254740991），或小于 -(253-1) 的整数。这是其内部表示形式导致的技术限制。

在大多数情况下，这个范围就足够了，但有时我们需要很大的数字，例如用于加密或微秒精度的时间戳。

BigInt 类型是最近被添加到 JavaScript 语言中的，用于表示任意长度的整数。


三、String 类型
JavaScript 中的字符串必须被括在引号里。

let str = "Hello"; let str2 = 'Single quotes are ok too'; let phrase = `can embed another ${str}`;

在 JavaScript 中，有三种包含字符串的方式。

双引号："Hello".
单引号：'Hello'.
反引号：`Hello`.



四、Boolean 类型（逻辑类型）
boolean 类型仅包含两个值：true 和 false。

这种类型通常用于存储表示 yes 或 no 的值：true 意味着 “yes，正确”，false 意味着 “no，不正确”。


五、Null 和 Undefined 类型
“null” 值
特殊的 null 值不属于上述任何一种类型。
特殊值 undefined 和 null 一样自成类型。

undefined 的含义是 未被赋值。

如果一个变量已被声明，但未被赋值，那么它的值就是 undefined




六、object 类型和 symbol 类型
object 类型是一个特殊的类型。

其他所有的数据类型都被称为“原始类型”，因为它们的值只包含一个单独的内容（字符串、数字或者其他）。相反，object 则用于储存数据集合和更复杂的实体。



七、typeof 运算符
typeof 运算符返回参数的类型。当我们想要分别处理不同类型值的时候，或者想快速进行数据类型检验时，非常有用。