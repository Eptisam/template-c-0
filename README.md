# C Module 0: Introduction

## Exercise 0.1
> Use the editor below to write your first C program mimicking the one above, but with a more creative message.

```
#include <stdio.h>
int main (){
  printf("My name is Eptisam\n");
}
```

## Exercise 0.2
> Type up and compile the above program.
> What is the compiler error reported
The compiler error is main.c:2:1: error: unknown type name "Int";


## Exercise 0.3
> What is the error produced by compiling this program?
Unknown refrence of Main. It has to be a lowercase m.

## Exercise 0.4
> What is the error produced by compiling this program?
Printf causes the error. It has to be a lowercase p.

## Exercise 0.5
> What is the error produced by compiling this program?
Forgot to close the paranthesis.

## Exercise 0.6
> What is the error produced by compiling this program?
Forgot to close the quotations. 

## Exercise 0.7
> What is the error produced by compiling this program?
Forgot the semi-colon.

## Exercise 0.8
> What is the error produced by compiling this program?
Forgot the closing brace.

## Exercise 0.9
> What is the error produced by compiling this program?
Forgot to state the method has to return something. Forgot the int.

## Exercise 0.10
> What kind of a compiler error do you get if you try to use a reserved word as an identifier? Use a reserved word to declare an integer identifier.
Expected identifier or have the reserved words in paranthesis.

## Exercise 0.11
> What happens if you omit the "L" or "LLU" when declaring numStarsInUniverse and largestIntegerInC? What happens if you use `%d` for the largestIntegerInC print statement?
I didn't see a difference but I know that for arithematic it won't provide the exact answer if it's omitted. It will be rounded. IF you use %d then it gives you a completely different answer.

## Exercise 0.12
> Adjust the amount of space used in the printf call. What happens if x has more digits than are reserved? What happens if it has fewer digits?
If x has more digits than the reserved amoount it will print the full number. If it has less than the digits reserved it will print a blank space until it gets to the reserved amount

## Exercise 0.13
> What print command would you use to print PI with a reserved width of 10 characters and only one digit after the decimal place? Does the reserved width include the decimal point and "e+" notation characters?
printf("float PI = %10.1f\n", PI) It includes the reserved width but no e notation.

## Exercise 0.14
> It's a common error to mistype the format string. What happens when you reverse the `%d` and `%f` specifiers in the program above?
It gives a warning about the format because using the wrong format for the data type. It still prints things out but the format is wierd and pritns the wrong number.

## Exercise 0.15
> What happens if you use double quotes when assigning a char? What happens if you put multiple letters within single quotes?
It gives a warning again and prints different values when using double quotes. Again more warnings when multiple letters are in the single quotes. Also prints the wrong values.

## Exercise 0.16
> Use the ASCII table above to assign `c1` and `c2` to numeric values that represent your initials. Then print them using both the `%d` and `%c` format specifiers.
#include <stdio.h>

int main ()
{
  char c1 = 69;
  char c2 = 75;
  
  printf ("as char = %c %c\n", c1, c2);
  printf ("as number = %d %d\n", c1, c2);
  printf ("as hex = 0x%x 0x%x\n", c1, c2);
}

## Exercise 0.17
> What is the program's output?
3.000000 is the output

## Exercise 0.18
>  Put the following code into the editor below. What does it print out? What is its significance?
There is also a warning, but 1 0 1 1 0 0 0 0 % also gets printed. It's signfigant because it's printing the boolean numerical value each time in the for loop

## Exercise 0.19
> What happens when you try to modify one of the `const` variables? Is this a compile-time or a run-time error?
You can't modify the constant variable and that is the compile time error


## Exercise 0.20
> There is a bug in this code! Why won't it print "i is not 5" like the developer expected? Is this a compile-time or run-time error?
It won't print i is not 5 because the if statement is incorrect. It has to be if (i==5) to get it to print i is not 5. It complies correctly it's just a run time error.  


## Exercise 0.21
> Without running it, what is the error in the code?
It's because it's missing the brackets. There should be one opening after the while statement and one closing after the i--;


## Exercise 0.22
> Use for-loops to print "hourglasses" of different sizes. Enter your code here:
I couldn't figure this in time. I got it to print the the top half of the while loop but the bottom half I couldn't do

```
// Paste your program here

```
