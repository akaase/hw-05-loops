# Assignment: Flow Control

## Learning Goals

In this assignment, you'll practice:

* Implementing conditionals: `if`, `elif`, and `else`
* Declaring and using Lists
* Using `for` and `while` loops

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

# Exercise 1: Mini-Quiz

The first exercise of this homework is a mini-quiz.

Put all of your answers into a file called `exercise1.txt`.

1. True or false: An `if` statement can live without an `else` statement.

1. True or false: An `else` statement can live without an `if` statement.

1. True or false: An `elif` statement can live without an `if` statement.

1. True or false: An `if` + `elif` statement can live without an `else` statement.

1. True or false: The following statements are equivalent.

   ```python
   if a == True:
   ```

   ```python
   if a:
   ```

1. In the following code block, what prints?

   ```python
   a = True
   b = True
   c = False

   if a:
       print('1')

   if b:
       print('2')

   if c:
       print('3')

   if a and b:
       print('4')

   if a and c:
       print('5')

   if b and c:
       print('6')

   if a or b:
       print('7')

   if a or c:
       print('8')

   if b or c:
       print('9')
   ```

1. In the following code block, what prints?

   ```python
   a = False
   b = True
   c = True

   if a:
       print('1')
   elif b:
       print('2')
   elif c:
       print('3')
   else:
       print('4')
   ```

---

# Exercise 2: Most Clocks Are Normal, But Some Are Cuckoo!

**Skill you're Practicing:** Writing Conditionals

For this problem, put your solution into a file called `exercise2.py`.

You're making a program for your coworkers that displays a message on their desktop's idle screen. Depending on the time of day, you want to print a different quote.

You'll create a variable, `time`, which has an integer value between zero and 23, representing the hour of the day in [military time](https://www.thebalancecareers.com/military-time-3356971), which is a 24-hour clock.

Write a conditional statement with Python code that prints exactly one message using the following rules:

* If the time of day is before 9 a.m. --> print the quote `'Morning is wonderful. Its only drawback is that it comes at such an inconvenient time of day.'`

* Otherwise if the time of day is before or exactly 4 p.m. --> print the quote `'Working hard or hardly working?'`

* Otherwise, if the time of day is before 8 p.m. --> print the quote `'How did it get so late so soon?'`

* Otherwise, if the time of day is before 10 p.m. --> print the quote `'A day without sunshine is like, you know, night.'`

* Otherwise, for any time 10 p.m. or later --> print the quote `'Burning the midnight oil!'`

## Starter Code

```python
time = 8

# Continue to write more code!
```

> **Hint:** Test your code with different values for time of day. Make sure you are only printing one statement, regardless of the value of `time`!

---

# Exercise 3: I Came, I 'Saur, I Conquered

**Skill you're Practicing:** Writing Conditionals with Multiple Conditions

For this problem, put your solution into a file called `exercise3.py`.

The mighty Tyrannosaurus Rex is the king of dinosaurs, and he does whatever he pleases. When he's hungry, he eats. When he's angry, he fights. When he's bored, he roars. When he's tired, he sleeps!

Write a conditional statement that selects one of the following actions for T-Rex based on his current mood. T-Rex's actions are ordered by precedence:

* If T-Rex is angry, hungry, and bored he will eat the Triceratops
* Otherwise if T-Rex is tired and hungry, he will eat the Iguanadon
* Otherwise if T-Rex is hungry and bored, he will eat the Stegasaurus
* Otherwise if T-Rex is tired, he goes to sleep
* Otherwise if T-Rex is angry and bored, he will fight with the Velociraptor
* Otherwise if T-Rex is angry or bored, he roars
* Otherwise T-Rex gives a toothy smile

## Starter Code

```python
angry = True
bored = True
hungry = False
tired = False

# Example `if` statement
# (This is just an example, you'll have to do much more!)
if bored:
    print('T-Rex roars! RAWR!')
```

---

# Exercise 4: IOU!

**Skill you're Practicing:** Writing `for` Loops to Iterate Over a List

Solve this problem in a file called `exercise4.py`.

You have a list of Disney characters and you want to find out if each of them contain `i`, `o`, or `u` in their names. Loop through each character in the list and print out the following:

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

# Exercise 5: Light Reading

Read through the examples in these two articles:

* [`for` loops](https://www.digitalocean.com/community/tutorials/how-to-construct-for-loops-in-python-3)
* [`while` loops](https://www.digitalocean.com/community/tutorials/how-to-construct-while-loops-in-python-3)

Then, answer the following questions in a file called `exercise5.txt`:

1. What is a nested loop?
1. Which kind of loop is based on a conditional statement: `while` loops or `for` loops?
1. When you want to iterate a specific number of times, would you typically use a `while` loop or a `for` loop?
1. Is it possible to loop through a string one letter at a time? What is the example given in the article?
1. Extrapolate from what you learned in the articles: Do you think a `for` loop could be nested inside a `while` loop? Why or why not?

---

# (STRETCH) Exercise 6: If You're Cold, Sit in a Corner. It's 90 Degrees!

**Skill you're Practicing:** Writing `while` Loops

Solve this problem in a file called `exercise6.py`.

Wow! It's 90 degrees Fahrenheit and you are sweating buckets! Luckily you have air conditioning, but it's really old and kind of finicky. It cools the room by three degrees and shuts off, so you have to keep turning it back on until the temperature gets to where you want it to be. Seventy five sounds much more pleasant than 90, so that's what you're shooting for.

* While the temperature is greater than 75 degrees Fahrenheit, print `'The temperature is XX — crank the AC!'`, and subtract 3 degrees from the temperature.

* Once the temperature is cool enough and the loop is done, print `'75. Ahh, that's better.'`

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

Now, go be like a T-Rex and do what you please!

![](https://media.giphy.com/media/1NFXnqVxzGr6w/giphy.gif)
