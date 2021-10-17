# Hello python Exercise
This is the first part of python series in Kaggle course!

##Exercise 1
Complete the code below:

```Python
###Q1
pi = 3.14159 # approximate
diameter = 3

# Create a variable called 'radius' equal to half the diameter
radius = diameter/2

# Create a variable called 'area', using the formula for the area of a circle: pi times the radius squared
area = pi*(radius**2)

```
##Exercise 2
Add code to the following cell to swap variables `a` and `b` (so that `a` refers to the object previously referred to by `b` and vice versa).

```Python
########### Setup code - don't touch this part ######################
# If you're curious, these are examples of lists. We'll talk about
# them in depth a few lessons from now. For now, just know that they're
# yet another type of Python object, like int or float.
a = [1, 2, 3]
b = [3, 2, 1]
q2.store_original_ids()
######################################################################
​
c = a
a = b
b = c
# Your code goes here. Swap the values to which a and b refer.
# If you get stuck, you can always uncomment one or both of the lines in
# the next cell for a hint, or to peek at the solution.
```
##Exercise 3
###3a Add parentheses to the following expression so that it evaluates to 1.

```Python
(5 - 3 )// 2
```
###3b Add parentheses to the following expression so that it evaluates to 0.
```Python
(8 - 3) * (2 - (1 + 1))
```
##Exercise 4
Alice, Bob and Carol have agreed to pool their Halloween candy and split it evenly among themselves.
For the sake of their friendship, any candies left over will be smashed. For example, if they collectively
bring home 91 candies, they'll take 30 each and smash 1.

Write an arithmetic expression below to calculate how many candies they must smash for a given haul.

```Python
# Variables representing the number of candies collected by alice, bob, and carol
alice_candies = 121
bob_candies = 77
carol_candies = 109

# involving alice_candies, bob_candies, and carol_candies
to_smash = (alice_candies + bob_candies + carol_candies) % 3
```
