# SENG102-Assignment

**->** In this assignment I solve the programming challenges in the "Starting out with C++" book by Tony Gaddis, starting from page 802 to page 809.
Here are the descriptions of each challenge.

**1. Date**

Design a class called Date. The class should store a date in three integers: month, day, and year. There should be member functios to print the date in three different forms.

Input validation: Do not accept values for the day greater than 31 or less than 1. Do not accept values for the month greater than 12 or less than 1.

**3. Employee Class**

Write a class named Employee that has the member variables for the name, ID number, department, and position of an employee.

The class should have three different constructors.

Write appropriate mutator functions that store values in these member variables and accessor functions that return the values in these member variables. Once you have written the class, write a separate program that creates three Employee objects to hold the data.

The program should store this data in the three objects and then display the data foreach employee on the screen.

**4. Car Class**

Write a class named Car that has the member variables for the year model, make of, and current speed of the car.

In addition to the constructor and accessor functions there should be a function called "accelerate" which should add 5 to the speed member variable each time it is called and a function called "brake" which should subtract 5 from the speed member variable each time it is called.

Demonstrate the class in a program that creates a Car object, and then calls the accelerate function five times. After each call to the accelerate function, get the current speed of the car and display it. Then, call the brake function five times. After each call to the brake function, get the current speed of the car and display it.

**5. Personal Information Class** 

Design a class that holds the following personal data: name, address, age, and phone number. Write appropriate accessor and mutator functions. Demonstrate the class by writing a program that creates three instances of it.

**6. RetailItem Class**

Write a class named RetailItem that holds data about an item in a retail store. The class should have the member variables description, unitsOnHand, and price.

Write a constructor that accepts arguments for each member variable, appropriate mutator functions that store values in these member variables, and accessor functions that return the values in these member variables. Once you have written the class, write a separate program that creates three RetailItem objects and stores the data in them.

**7. Inventory Class**

Design an Inventory class that can hold information and calculate data for items in a retail store’s inventory. The class should have the private member variables itemNumber, quantity, cost, and totalCost.

The class should have two constructors, and appropriate accessor and mutator functions.

Do not accept negative values for item number, quantity, or cost.

**8. TestScores Class**

Design a TestScores class that has member variables to hold three test scores. The class should have a constructor, accessor, and mutator functions for the test score fields and a member function that returns the average of the test scores. Demonstrate the class by writing a separate program that creates an instance of the class. The program should ask the user to enter three test scores, which are stored in the TestScores object. Then the program should display the average of the scores, as reported by theTestScores object.

**9. Circle Class** 

Write a Circle class that has the following member variables which store a double value: radius and pi(3,14159).
The class should have two constructors, accessors, and mutators for the radius. In addition there should be functions to get the area, diameter, and circumference.

Write a program that demonstrates the Circle class by asking the user for the circle’s radius, creating a Circle object, and then reporting the circle’s area, diameter, and circumference.

**10. Population** 

In a population, the birth rate and death rate are calculated as follows: 

Birth Rate = Number of Births ÷ Population 

Death Rate = Number of Deaths ÷ Population

Design a Population class that stores a population, number of births, and number of deaths for a period of time. Member functions should return the birth rate and death rate. Implement the class in a program. Do not accept population figures less than 1, or birth or death numbers less than 0.

**11. Number Array Class** 

Design a class that has an array of floating-point numbers. The constructor should accept an integer argument and dynamically allocate the array to hold that many numbers. The destructor should free the memory held by the array. In addition, there should be member functions to perform the following operations:

• Store a number in any element of the array 

• Retrieve a number from any element of the array

• Return the highest value stored in the array 

• Return the lowest value stored in the array 

• Return the average of all the numbers stored in the array

**12. Payroll** 

Design a PayRoll class that has data members for an employee’s hourly pay rate, number of hours worked, and total pay for the week. Write a program with an array of seven PayRoll objects. The program should ask the user for the number of hours each employee has worked and will then display the amount of gross pay each has earned. Do not accept values greater than 60 for the number of hours worked.

**14. Fishing Game Simulation**

For this assignment, you will write a program that simulates a fishing game. In this game, a six-sided die is rolled to determine what the user has caught. Each possible item is worth a certain number of fishing points. The points will not be displayed until the user has finished fishing, and then a message is displayed congratulating the user depending on the number of fishing points gained.

**15. Mortgage Payment**

Design a class that will determine the monthly payment on a home mortgage. The class should have member functions for setting the loan amount, interest rate, and number of years of the loan. It should also have member functions for returning the monthly payment amount and the total amount paid to the bank at the end of the loan period. Implement the class in a complete program. Do not accept negative numbers for any of the loan values.

**16. Freezing and Boiling Points**

Design a class that stores a temperature in a temperature member variable and has the 
appropriate accessor and mutator functions. In addition to appropriate constructors, 
the class should have the following member functions: 

• isEthylFreezing. This function should return the bool value true if the tem- 
perature stored in the temperature field is at or below the freezing point of ethyl 
alcohol. Otherwise, the function should return false. 

• isEthylBoiling. This function should return the bool value true if the tempera- 
ture stored in the temperature field is at or above the boiling point of ethyl alcohol. 
Otherwise, the function should return false. 

• isOxygenFreezing. This function should return the bool value true if the tem- 
perature stored in the temperature field is at or below the freezing point of oxygen. 
Otherwise, the function should return false. 

• isOxygenBoiling. This function should return the bool value true if the tem- 
perature stored in the temperature field is at or above the boiling point of oxygen. 
Otherwise, the function should return false. 

• isWaterFreezing. This function should return the bool value true if the tem- 
perature stored in the temperature field is at or below the freezing point of water. 
Otherwise, the function should return false. 

• isWaterBoiling. This function should return the bool value true if the tem- 
perature stored in the temperature field is at or above the boiling point of water. 
Otherwise, the function should return false. 

Write a program that demonstrates the class. The program should ask the user to enter 
a temperature and then display a list of the substances that will freeze at that tempera- 
ture and those that will boil at that temperature.

**17. Cash Register**

Design a CashRegister class that can be used with the InventoryItem class discussed 
in this chapter. The CashRegister class should perform the following: 

1. Ask the user for the item and quantity being purchased. 

2. Get the item’s cost from the InventoryItem object. 

3. Add a 30% profit to the cost to get the item’s unit price. 

4. Multiply the unit price times the quantity being purchased to get the purchase sub- 
total. 

5. Compute a 6% sales tax on the subtotal to get the purchase total. 

6. Display the purchase subtotal, tax, and total on the screen. 

7. Subtract the quantity being purchased from the onHand variable of the 
InventoryItem class object. 

Implement both classes in a complete program. Feel free to modify the InventoryItem 
class in any way necessary. Do not accept a negative value for the quantity of items being 
purchased.

**18. A Game of 21**

For this assignment, you will write a program that lets the user play against the computer in a variation of the popular blackjack card game. In this variation of the game,two six-sided dice are used instead of cards. The dice are rolled, and the player tries to beat the computer’s hidden total without going over 21. 
Here are some suggestions for the game’s design:

• Each round of the game is performed as an iteration of a loop that repeats as long 
as the player agrees to roll the dice, and the player’s total does not exceed 21. 

• At the beginning of each round, the program will ask the users whether they want 
to roll the dice to accumulate points. 

• During each round, the program simulates the rolling of two six-sided dice. It rolls 
the dice first for the computer, and then it asks the user if he or she wants to roll. 
(Use the Die class that was demonstrated in this chapter to simulate the dice). 

• The loop keeps a running total of both the computer and the user’s points. 

• The computer’s total should remain hidden until the loop has finished. 

• After the loop has finished, the computer’s total is revealed, and the player with the 
most points without going over 21 wins.

**19. Trivia Game**

In this programming challenge you will create a simple trivia game for two players. The program will work like this: 

• Starting with player 1, each player gets a turn at answering five trivia questions. (There are a total of 10 questions.) When a question is displayed, four possible answers are also displayed. Only one of the answers is correct, and if the player selects the correct answer he or she earns a point. 

• After answers have been selected for all of the questions, the program displays the number of points earned by each player and declares the player with the highest number of points the winner.

In this program you will design a Question class to hold the data for a trivia question. The Question class should have member variables for the following data: A trivia question, Possible answer #1, Possible answer #2, Possible answer #3, Possible answer #4, The number of the correct answer (1, 2, 3, or 4).
The Question class should have appropriate constructor(s), accessor, and mutator 
functions. The program should create an array of 10 Question objects, one for each trivia question. Make up your own trivia questions on the subject or subjects of your choice for the objects.
