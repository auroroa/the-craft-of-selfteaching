# 一个拖延、焦虑症的启程之路

## 20190324
关注好几天了，终于走出了第一步，熟悉一下 Git 的基本操作，向源仓库 pull request 一个“被”字。


## 20190325
我是一个使用 Python 的人，但没系统学习过，借此机会对其中的知识点查漏补缺。同时观摩下不同领域人理解编程的视角。

### Part.1.E.1.entrance
The Logician and the Engineer: George Boole and Claude Elwood Shannon Created The Information Age.
> - 乔治·布尔(George Boole)发明 **布尔代数** 
> - -《The mathematical analysis of logic》使用代数形式表达逻辑思想
> - -《An investigation of the laws of thought》探索心智推理的基本规律、用微积分的符号语言进行表达，并在此基础上建立逻辑和构建方法的科学……
> - 克劳德·香农(Claude Elwood Shannon)发明 **逻辑电路**
> - 所谓“程序”不过是一系列 **布尔运算（Boolean Operations）**
> - 计算机强大的原因在于它 **可编程（Programable）**,即**流程控制（Control Flow)**
> - 任何一个逻辑表达式都会返回一个 **布尔值（Boolean Value）**

### Part.1.E.2.values-and-their-operators
> - 计算机程序由两部分组成：**运算（Evaluation）**、**流程控制（Control Flow）**
> - **常量（Literals）** 和 **变量（Variables）**
> - Python 中每个函数都有返回值，未指定则返回 **None**

### Part.1.E.3.control-flow
> 大多数编程语言都提供两种循环结构
> - **Collection-controlled loops** 
> - **Condition-controlled loops**

### Part.1.E.4.functions
> 函数参数包含两类
> - 位置参数（Positional Arguments，arg)
> - 关键字参数（Keyword Arguments，karg）

## 20190326
### Part.1.E.5.strings
> - 人机交互之间的信息转换（数值-二进制、字符串-数值-二进制、None-0），小数的精度损耗
> - Unicode（编码方式）、UTF（实现方式 Unicode Transformation Format）
> - Unicode 单字符码值转换函数：ord()、chr()
> - 关于换行符：Windows（\r\n）、Unix 类（\n）
> - 字符串：有序容器（Container）
> - 类对象（Class str）方法（Methods）：
> - 1. 大小写转换：str.upper()、str.lower()、str.capitalize() #句首字母大写、str.title() #每个单词首字母大写、str.swapcase() #逐个单词大小写转换、str.encode() #编码
> - 2. 搜索与替换：str.count(sub [,start, [end]])、str.find()、str.index()、str.startswith()、str.endswith()、str.replace(old, new [, count])、str.expandtabs(tabsize=8)、str.strip(['']) #默认去重空格、换行、TAB
> - 3. 字符串拆分、拼接：str.splitlines()、str.split(sep=None, maxsplit=-1)、str.join(_iterable_)
> - 4. 字符串排版：str.center(width [, fillchar])、str.rjust(width [, fillchar])、str.zfill(length) #用 0 填充为指定长度的字符串
> - 5. 字符串格式化：str.format(*args, **kwargs)

### Part1.E.6.containers
> - 数据容器：字符串、range()、List、Tuple、Set、Dictionary，容器中元素可被迭代（Iterate）
> - 可变容器（Mutable）：List、Set、Dictionary，不可变容器（Immutable）：字符串、range()、Tuple
> - List
> - - [2**x for x in range(8)]
> - - [2**x for x in range(8) if x%2==0]
> - List 是可变序列，字符串（str）是不可变序列（字符串常量，string literal），字符串不可根据索引删改，字符串的函数操作也不改变字符串本身，而是在操作后返回值给另一个变量
> - 可变序列 Methods：sort()、append()、clear()、copy()、extend(x)、insert(i, x)、pop(i)、reserve()、remove(x)（如果有多个 x，只删除第一个）……
> - Tuple 是不可变序列，当执行 **t = (1,2) \n t += 1,** 的时候，实际是产生了新的 Tuple
> - 集合初始化：set()，序列转集合自动去重 set("sakdk")
> - 集合运算：并集（|）、交集（&)、差集（-）、对称差集（^ = | - &）


## 20190408
停一次就停了十二天，加油！

### Part.1.E.7.files
> - 文件打开模式（'w'写入（重建）、'x'排他模式，如果文件已存在则打开失败、'a'追加、'b'二进制、'+'读写模式（更新））
> - os.path.exists(f.name)、os.remove(f.name)
> - readlines()，每一行都有一个换行符 '\n'


## 20190409
### Part.1.F.deal-with-forward-references
> - for ... else
> - 从容面对 **Forward Reference**（过早引用）
> - 读不懂也要读完，然后重复很多遍。（[(The Python Tutorial](https://docs.python.org/3/tutorial/index.html)、[PEP(Python Enhancement Proposals)](https://www.python.org/dev/peps/pep-0008/))
> - 磨炼 **只字不差** 的能力
> - 好的记忆很重要，最简单实用的方法是马上“总结、归纳、整理、组织” 关键知识点

| Containers in Python |
|:-----------------------:|

| Sequence Type | Set | Map |
|:--------------:|:-----:|:-----:|
| ***String*** | Set | Dictionary |
| *List*  | **Frozen Set** ||
| ***range()*** | |
| ***Tuple*** |  |
| ***Bytes*** |  |

| Immutable: Bold，Ordered: Italic |
|-----:|


## 20190410
### Part.1.G.The-Python-Tutorial-local
> - 使用官方指南，因为它更全面、权威、准确，其他工具可能只是更适合“入门”
> - [Guido van Rossume](https://gvanrossum.github.io/)
> - <queriess> site:python.org

### Part.2.A.Clumsy-and-patience
> - 笨拙与耐心（学-练-用-造）
> - 人生漫长，何必惊慌
> - Forward references 的知识结构太多，保持耐心，充分预算

### Part.2.B.Deliberate-practicing
> - 不刻意练习，就是在混时间


## 20190411
### Part.2.C.why-start-from-writing-functions
> - [Python Demo](https://github.com/python/cpython/tree/master/Tools/demo)

### Part.2.D.1-2-args
> - 闰年（ year % 4 == 0 and (year % 100 != 0 or year % 400 == 0)
> - 注意可变容器（如 List/Set/Dictionary）作为参数传递会改变原始值，好习惯是对此类参数先创建拷贝如：b = a.copy()
> - Order  of Arguments : Positional - Arbitrary positional - Keyword - Arbitrary keyword （ def say_hi(greeting='Hello', *names, capitalized=False, **other)）


## 20190412
### Part.2.D.3-lambda
> - id(variable) 获取变量内存地址
> - lambda 常用过即弃，比如结合 map(function, iterable, ...)


## 20190418
### Part.2.D.4-recursion
```
def teach_yourself(anything):
    while not create():
        learn()
	prictice()
    return teach_yourself(another)

teach_yourself(coding)
```
> - [Think Python: How to Think Like a Computer Scientist](http://greenteapress.com/thinkpython2/html/index.html)


### Part.2.D.5-docstrings
> - Docstring 规范: 三个双引号、内部文字前后不应有空行、第一行概要再空行再详情、尽量完善包含参数、返回值、可能的错误触发、函数限制等
> - Docstring 调用：foo.__doc__、help(foo)

### Part.2.D.6-modules
> - 任何一个 .py 的文件都可以被称为**模块（Module）**
> - import 模块的系统自动检测顺序：内建模块(sys.builtin_module_names) - sys.path 包含的目录(可通过 sys.path.append("/../..")添加搜索位置，当前路径排第一，append 路径排最后) 
> - from mycode import xx(*) 的逻辑：当前目录存在 mycode.py 文件则从该模块中导入，如果不存在则检测是否有 mycode 文件夹以及该文件夹中是否包含 __init__.py 文件，如果存在则导入指定模块(也可以这样：import mycode.xx)
> - dir() 函数可以查看可以触达的变量名称和函数名称



