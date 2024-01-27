# python_list_Listconcatination_cp20

Tutorial :- List Concatenation

Let's break down the problem into smaller steps:
Step 1: Understanding the Problem

We are given a list and an integer. We need to concatenate the given number to the list, and create two new lists. In the first list, the given number should be added at the beginning, and in the second list, the given number should be added at the end.
Step 2: Reading Input

We will use the input()
 function to read the input from the user. This function reads a line of text from the console and returns it as a string.
PYTHON
Step 3: Concatenating the Number

We can concatenate the given number to the existing list using the +
 operator. However, before doing this, we need to convert the input string to an integer.
PYTHON

In the above code snippet, we first convert the input string number
 to an integer using the int()
 function. Then, we concatenate the number to the list my_list
 using the +
 operator, and create the new list new_list
. Note that we put the given number inside square brackets to make it a single-element list.
Step 4: Creating the Two New Lists

We can create the two new lists by slicing the new_list
 in different ways.
PYTHON

In the above code snippet, we create the first list list1
 by concatenating the given number with the original list my_list
 using the +
 operator. We create the second list list2
 by concatenating the original list my_list
 with the given number using the same +
 operator.
Step 5: Printing the Output

Finally, we print the two new lists using the print()
 function.
PYTHON

Now that we have all the steps, we can easily put them together into one complete program
