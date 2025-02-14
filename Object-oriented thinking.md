
> ## 11.7 Polymorphism
> _Polymorphism means that a variable of a supertype can refer to a subtype object_.
> 
> The three pillars of object-oriented programming are [[Encapsulation]], [[inheritance]], and [[polymorphism]].
---
### Chapter 10 summary  

1. The procedural paradigm focuses on designing [[method]]s. The [[object]]-oriented paradigm doubles data and methods together into objects,. Software design using the object-oriented paradigm focuses on objects and operations on objects. The object-oriented approach combines the power of the procedural paradigm with an added dimension that integrates data with operations into objects.  

  
2. Many Java methods require the use of objects as [[argument]]s. Java offers a convenient way to incorporate, or wrap, a primitive data type into an object (e.g. wrapping `int` into the `Integer` class, and wrapping `double` into the `Double` class).  
  
     
3. Java can automatically convert a primitive-type value to its corresponding [[wrapper object]] in the context and vice versa.  
  
     
4. The `BigInteger` [[class]] is useful for computing and processing integers of any size. The `BigDecimal` class can be used to compute and process floating-point numbers with any arbitrary precision.  
  
     
5. A `String` object is immutable; its contents cannot be changed. To improve efficiency and save memory, the JVM stores two literal strings that have the same character sequence in a unique object. This unique object is called an _interned string object_.  
  
     
6. A _regular expression_ (abbreviated _regex_) is a string that described a pattern for matching a set of strings. You can match, replace, or split a string by specifying a pattern.  
  
     
7. The `StringBuilder` and `StringBuffer` classes can be used to replace the `String` class. The `String` object is immutable, but you can add, insert or append new contents into `StringBuilder` and `StringBuffer` objects. Use `String` if the string contents do not require any change and use `StringBuilder` or `StringBuffer` if they might change.