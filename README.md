# Java-To-Kotlin
Kotlin is a cross-platform, statically typed, general-purpose programming language with type inference. Kotlin is designed to interoperate fully with Java, and the JVM version of Kotlin's standard library depends on the Java Class Library, but type inference allows its syntax to be more concise.


## Print to Console

Java 

    // cursor will point to at the end of line
    System.out.print("Hello World");

    // cursor will point to at the start of new line
    System.out.println("Hello World");
    
Kotlin

    // cursor will point to at the end of line
        print("Hello World")
    
    // cursor will point to at the start of new line
        println("Hello World")

## Constant and Variable

Java

    // variable - String is immutable in Java because of the security, synchronization and concurrency, caching, and class loading.
    String name="Kingbond";
    
    // constant - String final is to destroy the immutability and to not allow others to extend it.
    final String name="Kingbond";
    
    
Kotlin

       // variable - var makes a variable mutable
       var name="Kingbond"
       
       // constant - val makes a variable immutable
       val name="Kingbond"
