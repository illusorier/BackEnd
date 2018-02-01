我们为什么需要Packages?

## Creating Packages

The types that are part of the Java platform are members of various packages that bundle classes by function.

Fundamental classes are in *java.lang*, classes for reading and writing (input and output) are in *java.io*.

You can put your types in packages too.

To create a package, you choose a name for the package and put a *package* statement with that 

        package graphics; 

If you do not use a *package* statement, your type ends up in an unnamed package.

It is a good practice to use names of packages with lower case letters to avoid any conflicts with the names of classes and interfaces.

## Using Package Members

The types that comprise a package are known as the *package member*.

