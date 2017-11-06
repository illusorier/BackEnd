Java项目的结构与前端项目的JS部分有一定差异。

因为Java是纯粹的面向对象语言，而JS本质是面向过程的。

In the Java programming language, every application must contain a **main** method.

Only one public class per Java file.

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