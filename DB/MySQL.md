什么是数据库？

A database is a separate application that stores a collection of data.

什么是MySQL?

MySQL is an open source SQL database.

检测本机mysql的版本，在命令行中输入：

    mysqladmin --version
    
当我们没有启动mysql时，在命令行中输入mysql，会得到以下结果：

    ERROR 2002 (HY000): Can't connect to local MySQL server through socket '/tmp/mysql.sock' (2)
    
在macOS中，我们可以通过软件启动mysql，也可以在命令行中直接启动。

     sudo /usr/local/mysql/support-files/mysql.server start
     
但当我们启动mysql后，在命令行中输入mysql，却得到了以下结果：

    ERROR 1045 (28000): Access denied for user 'weiyehui'@'localhost' (using password: NO)

当启动mysql后，在命令行中输入以下命令，我们便可以作为管理员登入mysql：

    mysql -u root -p
    
