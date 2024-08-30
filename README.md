# Ice-Cream-Parlor

Your local ice cream shop would like to set up a touchscreen tablet on the counter for their customers to customise their ice cream order and automatically calculate the cost of their ice cream.

Here are the options available when ordering an ice cream:
![image](https://github.com/user-attachments/assets/a5833217-8bbd-4c8a-a6e9-124db8078b56)

The new system will need a computer program to let the customer pick up their options for their ice cream. The customer should be able to specify:

 Whether they would like their ice cream to be served in a cup or on a cone
 How many scoops they would like to order (between 1 and 4)
 Whether they would like to add a flake
 Whether they would like to add some chocolate sprinkle
 Whether they would like to add a strawberry coulis (syrup)

Based on the user inputs and the price list provided above, the system should automatically calculate and display the total price of the chosen ice cream.

Step 1: Draw a Flowchart for your algorithm
Before attempting to complete the code for this task, grab a piece of paper and draw the flowchart to identify the key inputs, decisions and calculations for your algorithm.

Step 3: Add validation checks
To make your program more robust, add some validation rules on your inputs so that:

 The user can only enter one of the two options: Cup or Cone when selecting the container for their ice cream.
 The user can only enter a number between 1 and 4 when entering the number of scoops.
 The user can only enter Yes or No when asked whether they would like to add a flake, chocolate sprinkle or strawberry coulis.

You can find out more about implementing validation checks in Python using this page (input validation tab). https://www.101computing.net/ice-cream-price-calculator/python-syntax/

Step 4: Test Plan
Once your code is complete, test it using the following test plan to make sure all your calculations are correct!

Test #	Input Values	                            Expected Output
#1	    Container: Cone
        Number of Scoops: 2
        Toppings: Chocolate sprinkle	            Ice Cream Price: £3.10	
----------------------------------------------------------------------
#2	    Container: Cup
        Number of Scoops: 3
        Toppings: Flake and Strawberry Coulis	    Ice Cream Price: £4.50	
---------------------------------------------------------------------
#3	    Container: Cup
        Number of Scoops: 6
        Toppings: None	                          Please enter a number of scoops between 1 and 4	
----------------------------------------------------------------------
#4	    Container: Cup
        Number of Scoops: 1
        Toppings: None	                          Ice Cream Price: £1.50	
---------------------------------------------------------------------

