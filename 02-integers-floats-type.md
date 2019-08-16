## Example 1 - Returned Value

Given two numbers as arguments, write a function that returns the sum of those numbers.

**Pseudocode:**

1. Define a function called `add()` with two arguments.
2. Instantiate a variable `sum` and set it equal to the sum of the two arguments.
3. Return `sum`

**Implementation (Python)**

```py
def add(first, second):
  sum = first + second
  return sum

add(4, 7)
# => 11
```

Write a function called “multiply” that multiplies two integer arguments together.

## Example 2 - Random Number

Given nothing, write a function that returns a random number between 0 and 100.

**Pseudocode:**

1. Import Python's native `random` library
2. Write a function called `random_num_below_one_hundred`
3. Use the random integer function inside of the random library to generate the random integer.
4. Return the random integer

**Implementation (Python)**

```py
import random

def random_num_below_one_hundred():
  random_num = random.randint(0,100)
  return random_num

random_num_below_one_hundred()
# => 43
```

## Example 3 - Check Type

Make a function called `check_type` that takes in one argument and prints out the argument's type.

**Pseudocode:**

1. Define a function called `check_type()` with one argument.
2. Pass the argument to the native python `type()` function to get the argument's type
3. Return the type

**Implementation (Python)**

```py
def check_type(obj):
  return type(object)

check_type(4)
# => int
```

## Off Road Challenges

1. 
