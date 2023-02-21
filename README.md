# IndividualAssignment
This repo contains assignments that I have done individually while pursuing my course work

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
