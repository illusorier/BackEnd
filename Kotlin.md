Kotlin module for JVM target.

Kotlin module for JavaScript target.

Kotlin provides the ability to target JavaScript.

It does so by transpiling Kotlin to JavaScript.

The current implementation targets ECMAScript 5.1 but there are plans to eventually target ECMAScript 2015 as well.

When you choose the JavaScript target, any Kotlin code that is part of the project 

### Why using Kotlin instead of JavaScript?

The first advantage is that 

Package specification should be at the top of the source file:

        fun sum(a: Int, b: Int): Int {
            return a + b
        }