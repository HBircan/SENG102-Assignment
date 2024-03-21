# SENG102-Assignment1

In this assignment I solve the programming challenges in the Starting Out with C++ book by Tony Gaddis starting from page 802 to page 809.
Here are the descriptions of each challenge.

1. Date

Design a class called Date. The class should store a date in three integers: month, day and year. There should be member functios to print the date in the following forms:

12/25/2014 

December 25, 2014 

25 December 2014 

Demonstrate the class by writing a complete program implementing it.
Input validation: Do not accept values for the day greater than 31 or less than 1. Do not accept values for the month greater than 12 or less than 1.

3. Employee Class

Write a class named Employee that has the following member variables:

name: A string that holds the employee’s name.

idNumber: An int variable that holds the employee’s ID number.

department: A string that holds the name of the department where the employeeworks.

position: A string that holds the employee’s job title.

The class should have the following constructors:

• A constructor that accepts the following values as arguments and assigns them to the appropriate member variables: employee’s name, employee’s ID number, department, and position.

• A constructor that accepts the following values as arguments and assigns them to the appropriate member variables: employee’s name and ID number. The department and position fields should be assigned an empty string ("").

• A default constructor that assigns empty strings ("") to the name, department, and position member variables, and 0 to the idNumber member variable.

Write appropriate mutator functions that store values in these member variables and accessor functions that return the values in these member variables. Once you have written the class, write a separate program that creates three Employee objects to hold the following data.

The program should store this data in the three objects and then display the data foreach employee on the screen.
