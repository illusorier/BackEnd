The best way to learn a programming language is by writing programs.

Byte

字节，一字节等于八位。

### What is a compiler?

Computers understand only one language and that language 

Because a computer can only understand machine language and humans wish to write in high level languages.

High level languages have to be re-written (translated) into machine language at some point.



Console programs are programs that use text to communicate
 
每个C++程序都包含一个或多个函数，其中一个必须

The function named **main** is a special function in all C++ program;

C++ uses a convenient abstraction 

A *stream* is an entity where a program can either insert or extract 

On most program environments, the standard output by default is the screen, and 

### Pointers

Variables 

For a C++ program, the memory of a computer is like a succession of memory cells, each one byte in size, and each with a unique address.



一连串

The address of a variable can be obtained by preceding the name of a variable with an ampersand sign, known as *address-of operator*.

        foo = &myvar;
        
This would assign the address of variable `myvar` to `foo`.

The actual address of a variable in memory cannot be known before runtime.

C++语言并未定义任何输入输出(IO)语句，如JavaScript就存在 `console.log` ，取而代之，包含了一个全面的标准库来提供IO机制。

    #include <iostream>
    int main()
    {
        std::

前缀 `std::` 指出cout和endl是定义

标准库定义的所有名字都在命名空间std中。

通过使用作用域(::)运算符来指出我们想使用定义在命名空间std中的名字cout。

命名空间作为附加信息来区分不同库中相同名称的函数、类、变量等。

使用了命名空间即定义了上下文

C++最初的一个设计焦点就是能定义使用上像内置类型一样自然的类类型(class type)

C/C++和Python、JavaScript不同，在声明变量时必须指定其类型：

    int i = 1；

C++定义了一套包括算术类型和空类型在内的基本数据类型。

算术类型分为两类：整型(包括字符和布尔类型在内)和浮点型。

算术类型的尺寸(也就是该类型数据所占的比特数)在不同机器上有所差别。

基本的字符类型是char，一个char的空间应确保可以存放机器基本字符集中任意字符对应的数字值。

除字符和布尔类型外，其他整型用于表示不同尺寸的整数。

计算机以比特序列存储数据，每个比特非0即1。

大多数机器的字节由8比特构成，字则由32或64比特构成，也就是4或8字节。

字这个概念存在的意义是什么？

大多数计算机将内存中的每个字节与一个数字(被称为"地址(address)")关联起来。

类型决定了数据所占的比特数以及该如何解释这些比特的内容。

头文件(header)使类或其他名字的定义可被多个程序使用的一种机制，程序通过`#include`指令使用头文件。

变量提供一个具名的、可供程序操作的存储空间。

C++的标识符(identifier)由字母、数字和下划线组成，其中必须以字母或下划线开头

复合类型(compound type)是指基于其他类型定义的类型。

引用必须被初始化

标准库类型**string**表示可变长的字符序列，使用string类型必须首先包含string头文件。

    #include <string>
    using std::string;
    
C++在C语言的基础上增加了面向对象编程

C++是一种面向对象的程序设计语言

类定义是以关键字class开头，后跟类的名称，类的主体包含在一对花括号中，类定义后必须跟着一个分号或一个声明列表。

    class Box {
      public:
        double length;
        double breadth;
        double height;
    };

类的实例的公共数据成员可以直接使用访问运算符(.)来访问。

    