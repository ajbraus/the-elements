# Chapter 1 - Print, Return, and String Interpolation

## Challenge 1 - Warm Greetings

Given nothing, make a function called “warm_greetings” that prints a greeting.

**Psuedocode:**

1. Define a function called “warm_greetings”.
2. Write a print statement with a warm greeting.

**Implementation (Python)**

```py
def greetings():
  print(“Warm Greetings!”)

greetings()
# => "Warm Greetings!"
```

## Challenge 2 - Greetings

Given a greeting message string, make a function called `greetings()` that has one argument called `msg` that prints the given greeting message string.

**Pseudocode:**

1. Define a function called `greetings()`.
2. Write a print statement and pass in the .

**Implementation (Python)**

```py
def greetings(msg):
  print(msg)

greetings("Hiya folks!")
# => "Hiya folks!"
```

## Challenge 3 - Salutations

Given a salutation string, make a function called `salutations()` that takes one argument called `msg`, make the function print a concatenation of the string `"Salutations!"` and the given message string.

**Pseudocode:**

1. Define a function called `salutations()`.
2. Write a print statement and pass in the message as a `msg` argument to the f-string interpolation.

**Implementation (Python)**

```py
def salutations(msg):
  print(f"Salutations! {msg}")

salutations("Great to see you!")
# => "Salutations! Great to see you!"
```

## Challenge 4 - Named Salutation

Given a salutation string, make a function called `salutations()` that takes one argument called `msg`, make the function print a concatenation of the string `"Salutations!"` and the given message string.

**Pseudocode:**

1. Define a function called `named_salutations()` with two arguments `name` and `msg`.
2. Write a print statement and pass in the name as a `name` argument and the message as a `msg` argument to the f-string interpolation.

**Implementation (Python)**

```py
def named_salutations(name, msg):
  print(f"Salutations! {name}, {msg}")

named_salutations("Mike", "Great to see you!")
# => "Salutations! Mike, Great to see you!"
```

## Challenges

1. Write a function that takes in a person's name as its only argument and print out the song happy birthday with their name where it belongs.
1. Write a function called `multiply()` that returns the multiplication of two numbers.
1. You want to make usernames unique, and you decide that by adding a random number to them that will make them more unique. Write a function called `make_username()` that takes in a string and concatenates it with a random number between 0-9999.

**Stretch**

1. You realize that some of your usernames are getting fewer than four digits. Make a new make_username function that always adds four digits to the username.
1. 
