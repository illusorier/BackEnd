Java代码的结构与前端项目的JS部分有一定差异。

因为Java是纯粹的面向对象语言，而JS本质是面向过程的。

In the Java programming language, every application must contain a **main** method.

Only one public class per Java file.

> If you put multiple types in a single source file, only one can be *public*, and it must have the same name as the source file.

## Background

A **JAR** (Java ARchive) is a package file format typically used to aggregate

**WAR** (Web application ARchive) files are used to distribute Java-based web applications.

## Classes and Objects

This is a class declaration:

        class MyClass extends MySuperClass implements YourInterface{
            // field, constructor, and 
            // method declarations
        }

The *class body* (the area between the braces).

Objects have two characteristics: They have **states** and **behaviors**.

The states and behaviors of an object, can be represented by variables and methods in the class respectively.

#### Declaring Member Variables

There are several kinds of variables:

- Member variables in a class - these are called fields. ( 成员变量 )

- Variables in a method or block of code - these are called local variables.

- Variables in method declarations - these are called parameters.

成员变量的组成：

Field declaration are composed of three components, in order:

1. Zero or more modifiers, such as *public* or *private*.
2. The field's type.
3. The field's name.

访问修饰符

The first (left-most) modifier is access modifier. 

- public modifier - the field is accessible from all classes.

In the spirit fo encapsulation, it is common to make fields private.

This means that they can only be directly accessed from the Class who defines it.

#### Static keyword

Static keyword can be used with class, variable, method and block.

Static members belong to the class instead of a specific instance.

        class SimpleStaticExample {
            // This is a static method
            static void myMethod()
            {
                System.out.println("myMethod");
            }
         
            public static void main(String[] args)
            {
                  /* You can see that we are calling this
                   * method without creating any object. 
                   */
                   myMethod();
            }
        }
        
We can call this method without any object because when we 

#### Final keyword

The final keyword can be applied with the variables, a final variable that have no value is called **blank final variable** or **uninitialized final variable**. 

Final variables once assigned a value can never be changed.

#### Super keyword

The super keyword refers to the objects of immediate parent class.

方法重载

Method Overloading is a feature that allows a class to have more than one method having the same name, if their argument lists are different.

#### Three ways to overload a method

In order to overload a method, the argument lists of the methods differ in either of these:

方法重写

Declaring a method in **sub class** which is already present in **parent class** is known as method overriding.

Overriding is done so that a child class can gave its own implementation to a method which is already provided by the parent class.

A class that is declared using "**abstract**" keyword is known as abstract class.

        class Human {
            public static void walk() {}
        }
        
        class Boy extends Human {
            public static void walk() {}
        }
        
#### Abstract Class 

抽象类 抽象方法

A class that is declared using "**abstract**" keyword is known as abstract class.

It can have abstract methods (methods without body ) as well as concrete methods ( regular methods with body ).

A normal class ( non-abstract class ) cannot have abstract methods.

> An abstract class can not be **instantiated**.

## Interface

Defining an interface is similar to creating a new class.

An interface can have methods and variables just like the class but 

## Multithreading

#### Creating a thread in Java

There are two ways to create a thread in Java:

1. By extending Thread class

2. By implementing Runnable interface

#### How to Create a Simple Web Server in Java?

什么是Http Server?

An Http Server is bound to an IP address and port number and listens for incoming requests and returns responses to clients.

        @Exported
        public abstract class HttpServer
        extends Object
        
One or more HttpHandler objects must be 

HttpContext represents a mapping 

泛型出现的原因

假如一个类的使用需要依赖其他若干个类，且具体依赖情况会发生变化

只能持有单个对象的类：

    class Automobile {}
    
    public class 
    

元组(tuple)是将一组对象直接打包存储于其中的