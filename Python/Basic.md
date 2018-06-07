角度：用Python做算法题、爬虫、多线程、多进程及异步的解决方案。

Python is a dynamic, interpreted (bytecode-compiled) language. 

There are no type declarations of variables, parameters, functions, or methods in source code.

This makes the code short and flexible, and 

Python中的变量、函数参数、函数返回值等声明时都无需附加类型信息。

这点与JavaScript十分类似。

Comments begin with a '#' and extend to the end of the line.

Python source files use the ".py" extension and are called "modules".

在命令行中运行python

    python3

A Python module can be run directly

Besides numbers, Python can also manipulate strings, 

在Python中函数是如何定义的？

One unusual 

The `def` keyword defines the function with its 

One unusual Python feature is that the whitespace indentation of a piece of code affects its meaning.

### Numbers

There are three distinct numeric types: *integers*, *floating point numbers*, *complex numbers*.

    import sys
    
    print(sys.float_info)
    
Numbers are created by numeric literals or as the result of built-in functions and operators.

数字的精度

With Python, it is possible to use the `**` operator to calculate powers.

If a variable is not "defined" (assigned a value), trying to use it will give you an error.

Operators with mixed type operands convert the integer operand to floating point:

### Strings

Besides numbers, Python can also manipulate strings, which can be expressed in several ways.

They 

The built-in function `len()` returns the length of a string:

    s = 'hello'
    print(len(s))
    
相应的代码在JS中是如何实现的：

    s = 'hello';
    console.log(s.length);

Python provides two levels of access to network services.