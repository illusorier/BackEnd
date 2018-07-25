我们通过输入输出来学习一些基本的C++知识。

C++语言并未定义任何输入输出(IO)语句，如JavaScript就存在 `console.log` ，取而代之，包含了一个全面的标准库来提供IO机制。

为什么要这么做？

iostream库包含两个基础类型**istream**和**ostream**，分别表示输入流和输出流。

一个流就是一个字符序列，是从IO设备读出或写入IO设备的。

术语"流"想要表达的是，随着时间的推移，字符是顺序生成或消耗的。

标准库定义了4个IO对象。

为了处理输入，我们使用一个名为**cin**的istream类型的对象，这个对象也被称为标准输入(standard input)。

对于输出，我们使用了一个名为**cout**的ostream类型的对象，这个对象也被称为标准输出(standard output)。

系统通常将程序所运行的窗口与这些对象关联起来。

    #include <iostream>
    int main()
    {
        std::count << "Enter two numbers"
        
问题来了，这个std，<<还有endl分别是什么?

还有，为什么C++的输入输出要搞得这么复杂？

注意到我们使用了`std::cout

前缀 `std::` 指出cout和endl是定义在名为**std**的命名空间中的。

标准库定义的所有名字都在命名空间std中。

main的函数体的第一条语句执行了一个表达式(expression)。

在C++中，一个表达式产生一个计算结果，它由一个或多个运算对象和(通常是)一个运算符组成。

这条语句中的表达式使用了**输出运算符(<<)**在标准输出上打印消息。

<<运算符接受两个运算对象

通过使用作用域(::)运算符来指出我们想使用定义在命名空间std中的名字cout。

命名空间作为附加信息来区分不同库中相同名称的函数、类、变量等。

使用了命名空间即定义了上下文

C++ I/O occurs in streams, which are sequences of bytes.

If bytes flow from a device like a keyboard, a disk drive, or a network connection etc. to main memory, this is called **input operation** and  

So far, we have been using the **iostream** standard library，