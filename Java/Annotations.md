## Annotations

Annotations have a number of uses, among them:

- Information for the compiler 

- Compile-time and deployment-time processing

- Runtime processing

In its simplest form, an annotation looks like the following:

        @Entity
        
The at sign character(@) indicates to the compiler that what follows is an annotation.

It is also possible to use multiple annotations on the same declaration.

#### Where Annotations Can Be Used

Annotations can be applied to declarations: declarations of classes, fields, methods, and other program elements.

When used on a declaration, each annotation often appears, by convention, on its own line.

#### Declaring an Annotation Type

The annotation type definition looks similar to an interface definition where the keyword `interface` is preceded by the at sign(@).

When we are talking about standard annotations like @Override - JVM is the consumer and it works at bytecode level.

That's something application developers can't control and can't use for custom annotations.

A set of annotation types are predefined in the Java SE API.

        @Exported
        
outside of the Java SE namespaces of  `java.*` and `javax.*` packages.

