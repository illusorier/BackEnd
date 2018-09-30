什么是变量，变量的本质？

While writing program in any language, you need to use various variables to store various information.

Variables are nothing but reserved memory locations to store values.

This means that when you create a variable you reserve some space in memory.

一个变量代表一部分指定的内存区域

变量提供一个具名的、可供程序操作的存储空间。

计算器就是一个很合适的，可以用来类比的对象，功能简单的计算器并没有如内存这样的存储功能，它只能完成一些简单的计算。

In computing, **memory** refers to the computer hardware integrated circuits that store information for immediate use.

在C++中变量是如何使用的，和其他主流的编程语言有哪些异同？

A variable definition tells the compiler where 

    type variable_list;
    
bool, char, int, float, double, void

C++ also allows to define various other types of variables.
    
Here, type must be a valid C++ data 

C/C++和Python、JavaScript不同，在声明变量时必须指定其类型：

    int i = 1；

C++中的每个变量都有其数据类型

变量定义的基本形式是：首先是**类型说明符(type specifier)**，随后紧跟由一个或多个变量名组成的列表，其中变量名以逗号分隔，最后以分号结束。

定义时还可以为一个或多个变量赋初值。

如果定义变量时没有指定初值，则变量被默认初始化(default initialized)，此时变量被赋予了"默认值"。

默认值到底是什么由变量类型决定

如果是内置类型的变量未被显示初始化，它的值由定义的位置决定。

每个类各自决定其初始化对象的方式。

而且，是否允许不经初始化就定义对象也由类自己决定。

