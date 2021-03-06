## Variables

Variables are at the heart of the language and provide the ability to read from and write to memory. In Go, access to memory is type safe. This means the compiler takes type seriously and will not allow us to use variables outside the scope of how they are declared.

## Zero Values
```
Boolean: false
Integer: 0
Floating Point: 0
Complex: 0i
String: "" (empty string)
Pointer: nil
```

## Notes

* When variables are being declared to their zero value, use the keyword var.
* When variables are being declared and initialized, use the short variable declaration operator `:=`.
* You don't need to use `:=` or type if an initializer (i.e. it has an initial value) is present, the type can be omitted; the variable will take the type of the initializer.

## Links

[Built-In Types](http://golang.org/ref/spec#Boolean_types)  
https://golang.org/doc/effective_go.html#variables  
http://www.goinggo.net/2013/08/gustavos-ieee-754-brain-teaser.html  
[What's in a name](https://www.youtube.com/watch?v=sFUSP8Au_PE)

## Code Review

[Declare and initialize variables](example1/example1.go) ([Go Playground](https://play.golang.org/p/B5mjJKPYLh))

## Exercises

### Exercise 1 

**Part A:** Declare three variables that are initialized to their zero value and three declared with a literal value. Declare variables of type string, int and bool. Display the values of those variables.

**Part B:** Declare a new variable of type float32 and initialize the variable by converting the literal value of Pi (3.14).

[Template](exercises/template1/template1.go) ([Go Playground](https://play.golang.org/p/JIgjb3Ty3e)) | 
[Answer](exercises/exercise1/exercise1.go) ([Go Playground](https://play.golang.org/p/wNjayRMEcM))
___
All material is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/LICENSE-2.0).
