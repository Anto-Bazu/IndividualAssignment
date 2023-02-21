# IndividualAssignment
This repo contains assignments that I have done individually while pursuing my course work

This C++ program demonstrates the concept of inheritance in object-oriented programming. It simulates a university registration system for courses and students.

The program creates a hierarchy of classes using inheritance, with the parent class being Course and child classes ICT, Law, and Business. The ICT class is further subclassed into Cert, Dip, and BSc-IT. The BSc-IT class is then subclassed into Stage_1, Stage_2, and Stage_3.

Each class has attributes and methods that reflect the characteristics of the course or stage. For instance, the Course class has an attribute name and a method print that prints the name of the course. The Stage_1 class, a child class of BSc-IT, has an additional attribute semester and a method print that prints the name of the course and the current semester.

The program then creates objects of these classes and calls their respective methods. For instance, it creates an object of the BSc-IT class and an object of the Stage_2 class, both with the name "Data Structures and Algorithms". It then calls the print method of each object, which prints the name of the course and the stage, respectively.

The program also creates a Student class that contains the attributes name, age, and registrationNumber. This class is used to create a Student object that is registered for a particular course. The Course class has an attribute students, which is a vector of Student objects. The program then adds a Student object to the students vector of a particular Course object.

Finally, the program cleans up after itself by deallocating the memory used by the dynamically allocated objects using the delete operator.
