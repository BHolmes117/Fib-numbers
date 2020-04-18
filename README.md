# Fib-numbers
4/17/2020

//This program will display how using fibonacci works in java.

To start with this program, you would want to make sure you have eclipse downloaded and have JDK.11, but it will work with either in your system. For computer hardware any PC is okay to work with.

To install this fibonacci program, you will want to read to how to compute fibonacci, After reading you want to start your program with the class and main method involved in it. With this in place input a scanner and 3 prinln for when the user enter an integer, when the reculisive number is and what the sum of the numbers lead up to are.

You would next have the fib add to another fib number to gain the next number. Here is my exmaple of what i mean:
public static long fib(long index) {
			if (index == 0) // Base case ?
				return 0;
			else if (index == 1) // Base case ?
				return 1;
			else // Reduction and recursive calls?
				return fib(index - 1) + fib(index - 2);
		}

