# fizzbuzz 

Read Me file for Jake's Fizzbuzz problem solving assignment
Author: Jacob Marlowe
Date:9/28/2024

Problem Solving FIZZBUZZ

1 Plan
What are the Inputs 
Desired Outputs
How to transformk given inputs into outputs piece by piece

2 Psuedocode

3 Divide and conquer

User will interact by entering number
Prompt user for a (positive integer only?) number in some way - (use popup prompt())
Print the number the user entered and every number before that counting up from starting number 1, except change any multiples of three in the count to print the string "Fizz", multiples of five print "Buzz", and if a multiple 3 & 5 print FizzBuzz.

Input is prompt with user to take in a number

Desired Output - Print the users number, and every number back to 1 interspersed with Fizz, Buzz, and FizzBuzz as described above.

-Prompt user for number
-Store user input into input/answer variable
-Initialize a counter variable that begins to count starting with number 1, stopping once it reaches the input number.
-Write function to count starting at number 1 until input number is reached
-Write function that outputs string "Fizz" for any number in the count divisible by three
-Write function that outputs string "Buzz" for any number divisible by five
-Write function that outputs string "FizzBuzz" for any numbers divisible by 3 and 5
-Create function to change count output to FizzBuzz when counter reaches any numbers divisible by both 5 and 3
Write function to print the results of the count