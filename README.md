# Prime Number Finder 

## Background
A prime number is an integer number greater than 1 that has no positive divisors other than one and itself. The table below are examples of some primes numbers.


## Directions
Write a program that will prompt the user for an integer <b>n</b> that will be tested to determine if it is a prime number. The best approach is to start by 
assuming the integer <b>n</b> is a prime number (<b>bool isPrime=true</b>) and attempting to prove it is not prime by testing it to find a number i that divides it evenly 
using the modulo (remainder) operator (i.e.  n%i==0 ).

Use a loop (a for loop is easiest) to repeatedly test the integer <b>n</b> to see if an i = 2, 3, 4, 5, . . . etc. up to <b>n</b>-1, is a divisor of the integer.  If you find a 
number that divides <b>n</b> evenly then you have proven that the number is not prime (isPrime=false) and the program exits from the loop. If a divisor is found to prove 
that the integer n is not prime, then output the smallest number that evenly divides the integer n.  If all possibilities are exhausted and no divisor was found that 
evenly divides integer <b>n</b> then the number must be prime (isPrime==true).



## Interface Prototype Example

### Test Case 1 Output
<pre><b>Enter an integer to test: 25
25 is a composite number because it is divisible by 5</b></pre>
### Test Case 2 Output
<pre><b>Enter an integer to test: 101
101 is a prime number</b></pre>
### Test Case 3 Output
<pre><b>Enter an integer to test: 10013
10013 is a composite number because it is divisible by 17
</b></pre>




