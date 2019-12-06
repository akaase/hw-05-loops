# Assignment: Loops

## Learning Goals

In this assignment, you'll practice:

* Declaring and using Lists
* Using `for` and `while` loops
* Reinforcing the concepts of conditionals: `if`, `elif`, and `else`

## Deliverables

1. **Fork** the assignment repo
1. Open your Terminal and navigate to your work folder (`cd $DEV`)
1. **Clone** your fork of the assignment repo onto your computer
1. Do your work inside your repo
1. **Commit** any new files that you create as well as any other changes
1. **Push** the changes to Github when you are done

## Submitting

To submit this assignment:

1. Go to the **assignment's main repo** (not your fork)
1. Click the **Issues** tab
1. Click the **New Issue** button
1. In the Title field, fill in your name
1. In the comment field, paste the URL to your assignment repo
1. Click **Submit new issue** and you're done!

---

# Exercise 1: IOU!

Solve this problem in a file called `exercise1.py`.

You have a list of Disney characters and you want to find out if each of them contain `i`, `o`, or `u` in their names.

Write a `for` loop to iterate over the list of characters and print out the following:

* If the name contains a 'u', print out the name plus `'U are so Uniquely U!'`
* Otherwise if the name contains an 'i', print out the name plus `"I bet you're Impressively Intelligent!"`
* Otherwise if the name contains an 'o', print out the name plus `'O My! How Original!'`
* Otherwise, print the name plus `"Ehh, a's and e's are so ordinary."`

## Starter Code

```python
disney_characters = ['simba', 'ariel', 'pumba', 'flounder', 'nala', 'ursula', 'scar', 'flotsam', 'timon']
```

## Expected Output

Be sure to run your code to see if the output is correct!

```
simba I bet you're Impressively Intelligent!
ariel I bet you're Impressively Intelligent!
pumba U are so Uniquely U!
flounder U are so Uniquely U!
nala Ehh, a's and e's are so ordinary.
ursula U are so Uniquely U!
scar Ehh, a's and e's are so ordinary.
flotsam O My! How Original!
timon I bet you're Impressively Intelligent!
```

> **Hint**: You can determine whether or not a string contains a particular character with an `if <substring> in <string>` statement. For example, `if 'b' in my_string:` will be `True` if `my_string` contains any `b`'s.

---

# Exercise 2: Light Reading

Read through the examples in these two articles:

* [`for` loops](https://www.digitalocean.com/community/tutorials/how-to-construct-for-loops-in-python-3)
* [`while` loops](https://realpython.com/python-while-loop/)

Then, answer the following questions in a file called `exercise2.txt`:

1. What is a nested loop?
1. Which kind of loop is based on a conditional statement: `while` loops or `for` loops?
1. When you want to iterate a specific number of times, would you typically use a `while` loop or a `for` loop?
1. Is it possible to loop through a string one letter at a time? What is the example given in the article?
1. Extrapolate from what you learned in the articles: Do you think a `for` loop could be nested inside a `while` loop? Why or why not?

---

# Exercise 3: If You're Cold, Sit in a Corner. It's 90 Degrees!

Solve this problem in a file called `exercise3.py`.

Wow! It's 90 degrees Fahrenheit and you are sweating buckets! Luckily you have air conditioning, but it's really old and kind of finicky. It cools the room by three degrees and shuts off, so you have to keep turning it back on until the temperature gets to where you want it to be. Seventy five sounds much more pleasant than 90, so that's what you're shooting for.

* While the temperature is greater than 75 degrees Fahrenheit, print `'The temperature is XX — crank the AC!'`, and subtract 3 degrees from the temperature.

* Once the temperature is cool enough (75 or lower) and the loop is done, print `'75. Ahh, that's better.'`

* Remember to use a `while` loop for this one!

## Starter Code

```python
temperature = 90
```

## Expected Output

Be sure to run your code to see if the output is correct!

```
Temperature is 90 — crank the AC!
Temperature is 87 — crank the AC!
Temperature is 84 — crank the AC!
Temperature is 81 — crank the AC!
Temperature is 78 — crank the AC!
75. Ahh, that's better.
```

> **Hint:** Make sure that your loop conditional is being updated with each iteration. Otherwise you'll end up with an infinite loop!

---

# All Done!

Time to get some rest!

![](https://media.giphy.com/media/13h8Y1oVRO30KQ/giphy.gif)
