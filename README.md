Download Link: https://assignmentchef.com/product/solved-cs115-introduction-to-programming-in-python-lab-03
<br>
<strong>Lab Objectives:</strong>  Functions​

<strong>Instructions:</strong>​ For this assignment, you are expected to use Spyder IDE. Upload your solutions as a single .zip file to the Lab03 assignment on Moodle before the end of your lab session. Use the following naming convention: SS_Lab03_Surname_FirstName.zip where SS is the section number 01, 02, 03, …, &amp; and Surname is your family name, &amp; FirstName is first name. You must attend your lab session to show and explain your solutions to your TA  and must answer their questions to get your grade by the end of your lab session (the week of Oct 22).

<strong><u>Important Note:</u></strong> You must be present in the lab from the beginning of your lab​    sessions. <u>​<strong>Otherwise, you will get 0 from this lab assignment.</strong></u>

<ol>

 <li>In this question, write a docstring for your function.

  <ol>

   <li>Write a function that takes an integer, n, as a parameter and displays an n-by-n matrix. Each element in the matrix is 0 or 1, which is generated randomly. ​<strong>Hint:</strong>​ You can generate a random integer number between x and y, inclusive, by using the function randint(x, y)​         ​.​ Write</li>

  </ol></li>

</ol>

import random  as the first statement in your program.




<ol>

 <li>Using your function from part a), write a program that prompts the user to enter a positive integer n and displays an n-by-n matrix.</li>

</ol>




​<strong>Sample run 1: </strong>

Enter a positive integer: 6

<ul>

 <li>0 1 1 1 1</li>

 <li>1 1 0 1 1</li>

 <li>1 1 0 1 0</li>

 <li>1 1 0 1 1</li>

 <li>1 1 0 1 0</li>

 <li>1 0 1 1 0</li>

</ul>

<strong>    Sample run 2: </strong>

Enter a positive integer: 3

0 0 1

<ul>

 <li>1 1</li>

 <li>0 1</li>

</ul>

<ol start="2">

 <li>In this question, write a docstring for your functions.</li>

</ol>




<ol>

 <li>Write a function named isPrime(i)​ ​ ​that takes a positive integer i &gt; 1 and returns True if it i is a prime number and False otherwise. Your function may assume that i &gt; 1. A number is a prime number if it has exactly two positive divisors: 1 and itself. However, 1 has only one positive divisor (1 itself), so it is not a prime number.</li>

</ol>




<ol>

 <li>Using your function from part a), write another function named listPrimes(a,​</li>

 <li>b) ​that takes integers a and b as input, and finds the prime numbers in the interval [a,b]. Your function may assume that 1 &lt; a &lt; b.</li>

</ol>




<ol>

 <li>Using your function from part b), write a program that inputs two integers a and b (1 &lt; a &lt; b) and display all prime numbers between a and b, inclusive. Your program must validate a &lt; b.</li>

</ol>




<strong>Sample run 1: </strong>

<strong> </strong>

Enter a positive integer a: 5




Enter another positive integer b (a must be less than b): 13

5 is a prime

7 is a prime

11 is a prime

13 is a prime




<strong>Sample run 2 </strong>

<strong> </strong>

Enter a positive integer a: 1




Enter another positive integer b (a must be less than b): 19

1 &lt; 1 &lt; 19 is NOT satisfied




<strong>Sample run 3 </strong>

<strong> </strong>

Enter a positive integer a: 19




Enter another positive integer b (a must be less than b): 5

1 &lt; 19 &lt; 5 is NOT satisfied<strong>  </strong>

<ol start="3">

 <li>In this question, write a docstring for your function.​</li>

</ol>




<ol start="12">

 <li>Write a function named throwUntil(x) ​ ​that takes integer x (2 ≤ x ≤ 12) as parameter, and throws a pair of dice randomly until their sum is equal to x, displays the values of dice with the given sum, and returns the number of rolls it takes to roll the given sum. Your function may assume that x is an int and  2 ≤ x ≤ 12.</li>

</ol>




<ol>

 <li>Write a program that inputs a sum between 2 and 12 from the user, and determines the value of two dice adding to the sum, and the number of times it takes to roll the dice. Your program should validate that the input sum is between 2 and 12 and prompt for another input until it is in the correct range.</li>

</ol>




<strong>     Sample run 1: </strong>




Enter sum of dice: 1

Sum must be between 2 and 12 inclusive




Enter sum of dice: 13

Sum must be between 2 and 12 inclusive




Enter sum of dice: 12

Die1 6 Die2 6

Dice are rolled 5 times to get the sum 12

<strong> </strong>

<strong>Sample run 2: </strong>




Enter sum of dice: 2

Die1 1 Die2 1

Dice are rolled 64 times to get the sum 2





