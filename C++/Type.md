While writing program in any language, you need to use 

A variable definition tells the compiler where 

    type variable_list;
    
bool, char, int, float, double, void

C++ also allows to define various other types of variables.
    
Here, type must be a valid C++ data 

变量提供一个具名的、可供程序操作的存储空间。

C++中的每个变量都有其数据类型

变量定义的基本形式是：首先是**类型说明符(type specifier)**，随后紧跟由一个或多个变量名组成的列表，其中变量名以逗号分隔，最后以分号结束。

定义时还可以为一个或多个变量赋初值。

如果定义变量时没有指定初值，则变量被默认初始化(default initialized)，此时变量被赋予了"默认值"。

默认值到底是什么由变量类型决定

如果是内置类型的变量未被显示初始化，它的值由定义的位置决定。

每个类各自决定其初始化对象的方式。

而且，是否允许不经初始化就定义对象也由类自己决定。

