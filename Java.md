Java项目的结构与前端项目的JS部分有一定差异。

因为Java是纯粹的面向对象语言，而JS本质是面向过程的。

In the Java programming language, every application must contain a **main** method.

Only one public class per Java file.

Java is a high level programming language.

A program written in high level language cannot be run on any machine directly.

First, it needs to be translated into that particular machine language.

## Classes and Objects

This is a class declaration:

        class MyClass extends MySuperClass implements YourInterface{
            // field, constructor, and 
            // method declarations
        }

The *class body* (the area between the braces).

#### Declaring Member Variables

There are several kinds of variables:

- Member variables in a class - these are called fields.

访问修饰符

The first (left-most) modifier is access modifier. 

- public modifier - the field is accessible from all classes.

In the spirit fo encapsulation, it is common to make fields private.

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

## Annotations

In its simplest form, an annotation looks like the following:

        @Entity
        
The at sign character(@) indicates to the compiler that what follows is an annotation.

It is also possible to use multiple annotations on the same declaration.

#### Where Annotations Can Be Used

Annotations can be applied to declarations: declarations of classes

When used on a declaration, each annotation often appears, by convention, on its own line.

#### Declaring an Annotation Type

The annotation type definition looks similar to an interface definition where the keyword `interface` is preceded by the at sign(@).

A set of annotation types are predefined in the Java SE API.

## Interface

Defining an interface is similar to creating a new class.

A **JAR** (Java ARchive) is a package file format typically used to aggregate

## Multithreading

#### Creating a thread in Java

There are two ways to create a thread in Java:

1. By extending Thread class

2. By implementing Runnable interface

