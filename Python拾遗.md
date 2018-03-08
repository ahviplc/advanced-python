https://zhuanlan.zhihu.com/p/33266239
# 语法
- 知道python的语法，缩进和符号对应的含义。
- 知道PEP8常见的范式以及代码格式化方法。
- 知道python所有关键字的含义和使用。
> del assert
- 知道python中大部分常用的类型（布尔值，字符串类型，数字类型，序列，集合，字典，生成器...）。
- 知道如何编写pythonic的代码（上下文管理器，推导表达式，装饰器，切片…）。
- 知道如何避免python中的一些坑，如可变的默认参数，闭包的迟绑定。
> 默认参数必须指向不可变对象
- 知道python 2.x和3.x的主要差异。
> http://www.runoob.com/python/python-2x-3x.html
- 知道python大多数常用的标准库以及其用途。
- 知道os和sys库常用的方法，和操作文件和目录的方式。
- 知道python中datetime库的常用操作。
- 知道普通文件/二进制文件读写的方式，知道StringIO和BytesIO的用途。
> StringIO和BytesIO用于内存读写
- 知道以单下划线开头、双下划线开头和双下划线包围的变量分别代表着什么含义。
> http://python.jobbole.com/81129/
- 知道python中的模块定义，以及导入模块的各种姿势。
- 知道知道global，local和nonlocal关键字在python中的含义和其使用场景。
> http://www.jb51.net/article/91422.htm
> http://www.jb51.net/article/57677.htm
- 知道python中==与is的区别。
> is 用于判断两个变量引用对象是否为同一个， == 用于判断引用变量的值是否相等。
- 知道for-else，try-else的含义和用途。

# 函数式
- 知道python中的函数式编程以及map、filter的使用。
- 知道装饰器中添加functools.wraps的含义与作用。
> functools.wraps 可以将原函数对象的指定属性复制给包装函数对象, 默认有 __module__、__name__、__doc__,或者通过参数选择。

# 虚拟机
- 知道python最常见的解释器有哪些。
- 知道python中弱引用的使用方式，知道python中gc的回收算法方式以及回收规则。
> http://python.jobbole.com/85431/
- 知道sys.settrace和sys.setprofile在python中的用途和使用方式。
> http://www.cnblogs.com/xuchunlin/p/7748311.html
- 知道.pyc文件的含义，清楚python代码大概的执行过程。
- 知道_在python解释器中的含义。
> "_"代表交互式解释器会话中上一条执行的语句的结果。

# 数据结构
- 知道list，tuple，dict，set等的时间复杂度和空间复杂度。
> http://www.orangecube.net/python-time-complexity
- 知道dict和set的常见操作，知道set之间集合运算的语法糖。
- 知道python中dict的底层实现，以及与OrderDict的关系。
https://github.com/python/cpython/blob/master/Lib/collections/__init__.py
- 知道dict和UserDict的关系，以及为什么有UserDict的存在。
https://www.cnblogs.com/xuchunlin/p/7763711.html
- 知道深拷贝和浅拷贝在python中的实现方式。
- 知道str，bytes和字符串编码的关系以及其相互转换的方法。
- 知道python代码的中文编码处理，以及如何处理乱码。
- 知道python中格式化字符串的方式以及其常见格式语法。
- 知道使用python中正则表达式的匹配、查找、切分和替换。
- 知道python中的几种字符串拼接方式与效率对比。
- 知道a = list()和a = []的区别。
- 知道如何利用collections，itertools，operator等模块来高效地操作容器对象。
- 知道python中序列化的常用库和接口（json，pickle）。
- 知道python中生成器的实现以及其使用场景。
- 知道python中抽象类的实现方式，以及其抽象基类模块，知道如何用python类实现一个抽象容器类型。

# 并发
- 知道GIL的限制以及与多线程的关系。
- 知道python中的多进程和多线程模型，知道多进程和多线程下间的通信实现。
- 知道进程池和线程池在python中对应的库和使用方式。
- 知道python中多线程间常用的同步原语的使用方式。
- 知道asyncio的使用方式和使用场景。

# 面向对象
- 知道python的命名空间查找规则（LEGB）。
- 知道python多继承的查找规则（MRO）。
> http://python.jobbole.com/85685/
- 知道property的含义以及其描述器实现。
- 知道__slots__的含义以及使用场景。
- 知道如何定义和使用元类，了解其使用场景。
- 知道python中type和object之间的关系。
- 知道鸭子类型（duck typing）的含义与其在python中的表现形式。
- 知道函数和方法的区别，知道绑定方法（bound-method）与未绑定方法（unbound-method）的关系。
- 知道__init__和__new__方法在class和type中分别的作用是什么。
- 知道类变量和实例变量的区别。
- 知道__dict__在类中的含义，以及类属性和方法与__dict__的关系。
- 知道普通方法，classmethod和staticmethod的区别。
- 知道__getattr__和__getattribute__的作用以及其顺序关系。
- 知道python中自省的使用方式，知道inspect库的常见用法。
- 知道python中常见的魔术方法和其使用方式。

# 其他（eg：工具）
- 知道python的调试工具（logging，pdb），知道unittest和doctest的使用。
- 知道python中的打包方式（setup.py）。
- 知道如何用python实现最常用的设计模式。
- 知道如何用python做web编程，以及WSGI协议是什么。
- 知道如何使用virtualenv，清楚其用途。
- 知道如何使用pip，以及其与requirements文件的关系。
- 知道Mixin模式以及在python中的用途。
- 知道python中性能测量的方式，如cProfile，tracemalloc。
- 知道python项目的文件/包的组织方式
