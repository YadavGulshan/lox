# Lox Language

Lox is a dynamically-typed programming language created for educational purposes. It is implemented in Java and inspired
by languages like C, Java, and Ruby. Lox supports features like variables, control flow statements, functions, classes,
and more.

## Getting Started

To start using Lox, you need to set up the development environment:

1. Install Java Development Kit (JDK) on your system.
2. Clone the Lox repository from [GitHub](https://github.com/yadavgulshan/lox).
3. Build the Lox interpreter using the provided build script.
4. Run the interpreter with a Lox script file as an argument.

## Syntax

### Comments

Use the `//` syntax for single-line comments:

```lox
// This is a comment
```

### Variables

Variables in Lox are dynamically-typed and use the var keyword for declaration:

```lox
var x = 42;
var message = "Hello, World!";
```

### Control Flow

If Statements
Use the if statement for conditional branching:

```lox
if (condition) {
  // Code to execute if the condition is true
} else if (anotherCondition) {
  // Code to execute if the anotherCondition is true
} else {
  // Code to execute if none of the conditions are true
}
```

While Loops
Use the while loop for repetitive execution:

```lox
while (condition) {
  // Code to execute repeatedly while the condition is true
}
```

### Functions

Functions in Lox can be defined using the fun keyword:

```lox
fun greet(name) {
  print "Hello, " + name + "!";
}

// Function call
greet("Alice");
```

### Classes

Lox supports object-oriented programming with classes:

```lox
class Person {
  init(name) {
    this.name = name;
  }

  sayHello() {
    print "Hello, my name is " + this.name + ".";
  }
}

// Creating an instance of the Person class
var alice = Person("Alice");
alice.sayHello(); // Output: Hello, my name is Alice.
```

### Running Lox Programs

Save your Lox code in a file with a .lox extension (e.g., hello.lox). Then, run the Lox interpreter from the command
line:

```lox
java -jar lox.jar hello.lox
```

