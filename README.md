# SENG102-Assignment

In this assignment I solve the programming challenges in the "Starting out with C++" book by Tony Gaddis starting from page 802 to page 809.
Here are the descriptions of each challenge.

1. Date
Design a class called Date. The class should store a date in three integers: month, day, and year. There should be member functios to print the date in three different forms.
Input validation: Do not accept values for the day greater than 31 or less than 1. Do not accept values for the month greater than 12 or less than 1.

2. Employee Class
Write a class named Employee that has the member variables for the name, ID number, department, and position of an employee.
The class should have three different constructors.
Write appropriate mutator functions that store values in these member variables and accessor functions that return the values in these member variables. Once you have written the class, write a separate program that creates three Employee objects to hold the data.
The program should store this data in the three objects and then display the data foreach employee on the screen.

3. Car Class
Write a class named Car that has the member variables for the year model, make of, and current speed of the car.
In addition to the constructor and accessor functions there should be a function called "accelerate" which should add 5 to the speed member variable each time it is called and a function called "brake" which should subtract 5 from the speed member variable each time it is called.
Demonstrate the class in a program that creates a Car object, and then calls the accelerate function five times. After each call to the accelerate function, get the current speed of the car and display it. Then, call the brake function five times. After each call to the brake function, get the current speed of the car and display it.

4. Personal Information Class 
Design a class that holds the following personal data: name, address, age, and phone number. Write appropriate accessor and mutator functions. Demonstrate the class by writing a program that creates three instances of it.

5. RetailItem Class 
Write a class named RetailItem that holds data about an item in a retail store. The class should have the member variables description, unitsOnHand, and price.
Write a constructor that accepts arguments for each member variable, appropriate mutator functions that store values in these member variables, and accessor functions that return the values in these member variables. Once you have written the class, write a separate program that creates three RetailItem objects and stores the data in them.

6. Inventory Class 
Design an Inventory class that can hold information and calculate data for items in a retail store’s inventory. The class should have the private member variables itemNumber, quantity, cost, and totalCost.
The class should have two constructors, and appropriate accessor and mutator functions.
Do not accept negative values for item number, quantity, or cost.

7. TestScores Class
Design a TestScores class that has member variables to hold three test scores. The class should have a constructor, accessor, and mutator functions for the test score fields and a member function that returns the average of the test scores. Demonstrate the class by writing a separate program that creates an instance of the class. The program should ask the user to enter three test scores, which are stored in the TestScores object. Then the program should display the average of the scores, as reported by theTestScores object.

8. Circle Class 
Write a Circle class that has the following member variables which store a double value: radius and pi(3,14159).
The class should have two constructors, accessors, and mutators for the radius. In addition there should be functions to get the area, diameter, and circumference.
Write a program that demonstrates the Circle class by asking the user for the circle’s radius, creating a Circle object, and then reporting the circle’s area, diameter, and circumference.

9. Population 
In a population, the birth rate and death rate are calculated as follows: 
Birth Rate = Number of Births ÷ Population 
Death Rate = Number of Deaths ÷ Population
Design a Population class that stores a population, number of births, and number of deaths for a period of time. Member functions should return the birth rate and death rate. Implement the class in a program. Do not accept population figures less than 1, or birth or death numbers less than 0.

10. Number Array Class 
Design a class that has an array of floating-point numbers. The constructor should accept an integer argument and dynamically allocate the array to hold that many numbers. The destructor should free the memory held by the array. In addition, there should be member functions to perform the following operations:
• Store a number in any element of the array 
• Retrieve a number from any element of the array
• Return the highest value stored in the array 
• Return the lowest value stored in the array 
• Return the average of all the numbers stored in the array

11. Payroll 
Design a PayRoll class that has data members for an employee’s hourly pay rate, number of hours worked, and total pay for the week. Write a program with an array of seven PayRoll objects. The program should ask the user for the number of hours each employee has worked and will then display the amount of gross pay each has earned. Do not accept values greater than 60 for the number of hours worked.
