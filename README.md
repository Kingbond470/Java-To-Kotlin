# Java-To-Kotlin
Kotlin is a cross-platform, statically typed, general-purpose programming language with type inference. Kotlin is designed to interoperate fully with Java, and the JVM version of Kotlin's standard library depends on the Java Class Library, but type inference allows its syntax to be more concise.


## Print to Console

### Java 

The cursor will point to at the end of line

     System.out.print("Hello World");

The cursor will point to at the start of new line

    System.out.println("Hello World");
    
### Kotlin

The cursor will point to at the end of line

        print("Hello World")
    
The cursor will point to at the start of new line

        println("Hello World")
        
        

## Constant and Variable

## Java

Variable - String is immutable in Java because of the security, synchronization and concurrency, caching, and class loading.

    String name="Kingbond";
    
Constant - String final is to destroy the immutability and to not allow others to extend it.

    final String name="Kingbond";
    
    
## Kotlin

Variable - var makes a variable mutable

       var name="Kingbond"
       
Constant - val makes a variable immutable

       val name="Kingbond"
       
## Assigning Null Value

### Java

null - a literal that represents a null reference, one that does not refer to any object. null is the default value of reference-type variables

       String name;
       name=null;
        
### Kotlin

null - In an effort to rid the world of NullPointerException, variable types in Kotlin don't allow the assignment of null.If you need a variable that can be null, declare it nullable by adding ? at the end of its type.

       var name: String?
       name=null
       
       
