# IndividualAssignment
This repo contains assignments that I have done individually while pursuing my course work

#Question 1
Computer Server Client Program
This program is written in C++ and consists of three classes: Computer, Server, and Client. The Computer class is the base class for the Server and Client classes, and contains the attributes and methods that are common to both subclasses. The Server and Client classes inherit from the Computer class and add additional attributes and methods that are specific to their respective roles.

Class Descriptions
Computer
The Computer class has the following attributes:

name (string): The name of the computer.
ip_address (string): The IP address of the computer.
os (string): The operating system running on the computer.
The Computer class has the following method:

ping: Takes a string argument ip_address and prints a message indicating that the computer is pinging the specified IP address.
Server
The Server class is a subclass of Computer, and has the following additional attribute:

num_users (int): The number of users connected to the server.
The Server class has the following additional method:

add_user: Increments the num_users attribute by 1 and prints a message indicating that a user has been added to the server.
Client
The Client class is a subclass of Computer, and has the following additional attribute:

server_ip (string): The IP address of the server that the client is connected to.
The Client class has the following additional method:

connect: Prints a message indicating that the client has connected to the server.
How to Use
To use this program, simply compile the code and run the resulting executable. The main function creates an instance of the Server class and an instance of the Client class, and calls their respective methods to demonstrate their functionality.

The program will output messages indicating that the server is pinging the client, that the client has connected to the server, and that a user has been added to the server.

#Question 2
This program is designed to demonstrate the implementation of inheritance in C++. It consists of two classes: Person and Student.

Person Class
The Person class is a parent class that contains three data members age, firstname and lastname. It has two member methods, getValues() and setValues(), which can be used to retrieve and modify the values of the data members, respectively. Additionally, the Person class has a constructor that initializes all of its data members when an object of the class is created.

Student Class
The Student class is a child class that inherits from the Person class. In addition to the data members inherited from the Person class, Student class has two additional data members: institution and year. It also has a registrationNumber data member. The Student class has its constructor that initializes all the data members including the data members inherited from the Person class.

Class Definitions
Person Class
Data Members
age: an integer representing the age of the person
firstname: a string representing the first name of the person
lastname: a string representing the last name of the person
Member Methods
getValues(): a member method that returns the values of the data members
setValues(): a member method that modifies the values of the data members
Constructor: initializes all the data members
Student Class
Data Members
age: an integer representing the age of the person
firstname: a string representing the first name of the person
lastname: a string representing the last name of the person
institution: a string representing the institution where the student is enrolled
year: an integer representing the year of study of the student
registrationNumber: a string representing the registration number of the student
Member Methods
Constructor: initializes all the data members including the data members inherited from the Person class.

#Question 3
This C++ program demonstrates the concept of inheritance in object-oriented programming. It simulates a university registration system for courses and students.

The program creates a hierarchy of classes using inheritance, with the parent class being Course and child classes ICT, Law, and Business. The ICT class is further subclassed into Cert, Dip, and BSc-IT. The BSc-IT class is then subclassed into Stage_1, Stage_2, and Stage_3.

Each class has attributes and methods that reflect the characteristics of the course or stage. For instance, the Course class has an attribute name and a method print that prints the name of the course. The Stage_1 class, a child class of BSc-IT, has an additional attribute semester and a method print that prints the name of the course and the current semester.

The program then creates objects of these classes and calls their respective methods. For instance, it creates an object of the BSc-IT class and an object of the Stage_2 class, both with the name "Data Structures and Algorithms". It then calls the print method of each object, which prints the name of the course and the stage, respectively.

The program also creates a Student class that contains the attributes name, age, and registrationNumber. This class is used to create a Student object that is registered for a particular course. The Course class has an attribute students, which is a vector of Student objects. The program then adds a Student object to the students vector of a particular Course object.

Finally, the program cleans up after itself by deallocating the memory used by the dynamically allocated objects using the delete operator.
