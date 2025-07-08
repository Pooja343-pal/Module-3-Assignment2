Module3-Assignment2-Task1
Task 1: Check if a Number is Even or Odd
Problem Statement:  Write a Python program that:
1. 	Takes an integer input from the user.
2. 	Checks whether the number is even or odd using an if-else statement.
3. 	Displays the result accordingly.

# Step 1: Take an integer input from the user
number = int(input("Enter an integer: "))

# Step 2 and 3: Check if the number is even or odd and display the result
if number % 2 == 0:
    print(f"{number} is even.")
else:
    print(f"{number} is odd.")

   Assignment 2 -task2
   Task 2: Sum of Integers from 1 to 50 Using a Loop
 
Problem Statement: Write a Python program that:
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.

   
   #  Initialize the sum variable
total_sum = 0

# Loop  from 1 to 50
for num in range(1, 51):
    total_sum += num  # Add each number to total_sum

#  Display the final sum
print(f"The sum of integers from 1 to 50 is: {total_sum}")

