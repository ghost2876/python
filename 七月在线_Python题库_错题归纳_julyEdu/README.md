# 七月在线，Python题库，使用新浪weibo账号登录

## 绿框为正确答案，红框为错误答案<

## 从错题中学习到的知识点
### isinstance() 与 type() 区别
type() 不会认为子类是一种父类类型，不考虑继承关系。<br />
isinstance() 会认为子类是一种父类类型，考虑继承关系。<br />
如果要判断两个类型是否相同推荐使用 isinstance()。<br />
### 可变对象与不可变对象的 区别Mutable vs Immutable Objects
不可变对象，该对象所指向的内存中的值不能被改变。当改变某个变量时候，由于其所指的值不能被改变，相当于把原来的值复制一份后再改变，这会开辟一个新的地址，变量再指向这个新的地址。<br />
可变对象，该对象所指向的内存中的值可以被改变。变量（准确的说是引用）改变后，实际上是其所指的值直接发生改变，并没有发生复制行为，也没有开辟新的出地址，通俗点说就是原地改变。<br />Python中，数值类型（int和float）、字符串str、元组tuple都是不可变类型。而列表list、字典dict、集合set是可变类型。<br />
https://www.cnblogs.com/sun-haiyu/p/7096918.html<br />
### python中list/tuple/dict/set的区别
参见python_notebook.ipynb<br />
list:  有序集合，key可以重复，随时增删改[]<br />
tuple: 有序集合，key可以重复，但一旦初始化就无法修改()<br />
dict:  键值对（key-value）方式存储，查找速度快{}<br />
set:   无序集合，key不能重复set()<br />
set一般是集合操作，比如并集、交集<br />
dict查找速度比set快，但是消耗内存大，用空间换时间<br />
### Python中Inf与Nan
Python中可以用float("inf")和float("-inf")表示正或负无穷，利用 inf(infinite) 乘以 0 会得到 not-a-number(NaN) 。如果一个数超出 infinite，那就是一个 NaN（not a number）数。<br />
无穷加减多少仍是无穷。<br />
不要在 Python 中试图用 is 和 == 来判断一个对象是否是正负无穷或者 NaN。你就乖乖的用 math 模块吧，否则就是引火烧身。如果你希望正确的判断 Inf 和 Nan 值，那么你应该使用 math 模块的 math.isinf 和 math.isnan 函数。<br />
### Python中的变量不必事先声明，但的确是区分大小写的
### 
### 
### 
### 
### 
### 
### 
### 
### 
### 