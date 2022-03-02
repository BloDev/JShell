# JShell
A mock Bash shell developed in Java within a team of four using the Agile Scrum methodology.

It incorporates many different Software Design patterns such as the Singleton, Dependency Injection, and Composite design pattern.

Object-Oriented principles such as encapsulation, abstraction, inheritance, and polymorphism were used during the development process to ensure reusable and maintainable code. More specifically, Object-Oriented guidelines such as the Single Responsibility and Liskov Substitution principle were followed.

Testing was done with JUnit.

Version control was done with SVN.

## Running the Program
### Prerequisites
- Project files
- JDK 11.0.8
### Compiling
Navigate inside of the `src` directory and run the following command:
```
$ javac commands/*.java containers/*.java driver/*.java system/*.java
```
### Executing
Run the following command inside of the same `src` directory:
```
$ java driver/JShell
```

## Supported Commands
- exit
- mkdir
- cd
- ls
- pwd
- pushd
- popd
- history
- cat
- curl
- echo
- man
- rm
- mv
- cp
- search
- tree
- saveJShell
- loadJShell

## Authors
- Brandon Lo
- Calvin Yuen
- Jahin Promit
- Tanzim Ahmed
