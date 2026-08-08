library management system

project description

this is a library management system developed using java and object-oriented programming (oop) concepts.

the system allows a library to manage books, members, authors, and borrowing records.
features

user login
admin and member roles
add books
view books
search books
update books
delete books
add members
borrow books
return books
view borrowing records
generate library reports
save data using file handling
input validation and error handling

oop concepts used

encapsulation
inheritance
polymorphism
abstraction
interface
method overloading
method overriding

technologies used

java
java oop
java file i/o
intellij idea

project structure

model - contains the main classes such as book, member, author, and user.
service - contains the main business logic.
exception - contains custom exception classes.
util - contains helper and utility classes.
main.java - starts the application.

how to run

open the project in intellij idea.
make sure java jdk 17 or later is installed.
open main.java.
run the main class.
follow the instructions shown in the console.

project type

object-oriented programming course project

author

student project

this is the structure how you will run the code
src
│
├── Main.java
│
├── model
│   ├── User.java
│   ├── Admin.java
│   ├── Member.java
│   ├── Author.java
│   ├── Book.java
│   └── Borrowing.java
│
├── service
│   ├── AuthService.java
│   ├── LibraryService.java
│   └── ReportService.java
│
├── exception
│   ├── BookNotFoundException.java
│   ├── BookAlreadyBorrowedException.java
│   └── InvalidInputException.java
│
└── util
├── FileManager.java
├── InputValidator.java
└── PasswordUtil.java