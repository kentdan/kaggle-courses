# Function Exercise
This is the second part of python series in Kaggle course!

##Exercise 1
Complete the body of the following function according to its docstring.
HINT: Python has a built-in function round.

```Python
"""Return the given number rounded to two decimal places.

    round_to_two_places(3.14159)
    3.14
    """
    def round_to_two_places(num):
        return round(num, 2)
    round_to_two_places(3.14159)
    pass
```
##Exercise 2
The help for `round` says that `ndigits` (the second argument) may be negative.
What do you think will happen when it is? Try some examples in the following cell.

```Python
round(338.4324123,ndigits=1)
```
##Exercise 3
In the previous exercise, the candy-sharing friends Alice, Bob and Carol tried to split candies evenly. For the sake of their friendship, any candies left over would be smashed. For example, if they collectively bring home 91 candies, they'll take 30 each and smash 1.

Below is a simple function that will calculate the number of candies to smash for *any* number of total candies.

Modify it so that it optionally takes a second argument representing the number of friends the candies are being split between. If no second argument is provided, it should assume 3 friends, as before.

Update the docstring to reflect this new behaviour.

```Python
def to_smash(total_candies, n_friends=3):
    return total_candies % n_friends

```
##Exercise 4 (optional)
It may not be fun, but reading and understanding error messages will be an important part of your Python career.

Each code cell below contains some commented buggy code. For each cell...

1. Read the code and predict what you think will happen when it's run.
2. Then uncomment the code and run it to see what happens. (**Tip**: In the kernel editor, you can highlight several lines and press `ctrl`+`/` to toggle commenting.)
3. Fix the code (so that it accomplishes its intended purpose without throwing an exception)

```Python
def ruound_to_two_places(num):
    return round(num,ndigits=3)
ruound_to_two_places(9.9999)
```

```Python
x = -10
y = 5
min(x, y)
```

```Python
def f(x):
 y = abs(x)
 return y

print(f(5))
```
