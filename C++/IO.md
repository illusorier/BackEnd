C++语言并未定义任何输入输出(IO)语句，如JavaScript就存在 `console.log` ，取而代之，包含了一个全面的标准库来提供IO机制。

iostream库包含两个基础类型**istream**和**ostream**，分别表示输入流和输出流。

一个流就是一个字符序列，是从IO设备读出或写入IO设备的。

术语"流"想要表达的是，随着时间的推移，字符是顺序生成或消耗的。

标准库定义了4个IO对象。

为了处理输入，我们使用一个名为**cin**的istream类型的对象，这个对象也被称为标准输入(standard input)。

对于输出

    #include <iostream>
    int main()
    {
        std::

前缀 `std::` 指出cout和endl是定义

为什么C++的输入输出要搞得这么复杂？

标准库定义的所有名字都在命名空间std中。

通过使用作用域(::)运算符来指出我们想使用定义在命名空间std中的名字cout。

命名空间作为附加信息来区分不同库中相同名称的函数、类、变量等。

使用了命名空间即定义了上下文

C++ I/O occurs in streams, which are sequences of bytes.

If bytes flow from a device like a keyboard, a disk drive, or a network connection etc. to main memory, this is called **input operation** and  

So far, we have been using the **iostream** standard library，