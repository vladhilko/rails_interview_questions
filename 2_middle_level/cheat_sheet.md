# Design/Patterns

## OOP

1. Explain the difference between public, protected and private methods
self (receiver)

## Design patterns

1. What is Singleton pattern? 
module/class has one reason to be changed

1. What is Decorator pattern?
1. What is Presenter pattern?
1. What is Adapter pattern?
1. What is Observer pattern?
1. What is Strategy pattern? ( connected with O from solid )

# Ruby

1. Why in Ruby 24 * 0.1 ≠ 2.4?
2.4000000000000004

1. What is proc, lambda, block? And what are the differences between them?
Blocks are used for passing blocks of code to methods, and procs and lambda’s allow storing blocks of code in variables.
Blocks are used extensively in Ruby for passing bits of code to functions. By using the yield keyword, a block can be implicitly passed without having to convert it to a proc.
When using parameters prefixed with ampersands, passing a block to a method results in a proc in the method’s context. Procs behave like blocks, but they can be stored in a variable.
Lambdas are procs that behave like methods, meaning they enforce arity and return as methods instead of in their parent scope.

## Design principles

1. What is DRY?
dont repeat yourself
1. What is SOLID?
is an acronym for five design principles intended to make software designs more understandable, flexible and maintainable. 

1. What is KISS?
Keep it simple, stupid

1. What is YAGNI?
You ain’t gonna need it
In general it says that we should code only things that are required from us in this particular moment.

1. What is TDA?
Tell don’t ask

1. What is SoC: Separation of Concerns?
Each class should be unique and separated from the rest.

1. What is The Single Responsibility Principle?
A module should be responsible to one, and only one, actor

1. What is The Open Closed Principle?
Generally, it is said that anything that gives a class a reason to change can be viewed as a responsibility

1. What is The Liskov Substitution Principle?
Classes or methods should be open for extension, but closed for modification. 

1. What is The Interface Segregation Principle?
1. What is The Dependency Inversion Principle?
