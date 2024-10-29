# Debugging my Life
## What is debugging?
**Debugging** is a term commonly used by programmers and developers to describe the act of looking for errors in code and correct them. By doing so, they are removing "bugs", or errors from their app. 

### Where did it come from and why?

**Bugs** have been used as the term since the first case originated from a real-life insect. A moth lodged in the machine's hardware was discovered by engineers working on Harvard University's Mark II Aiken Relay Calculator in 1947.

<img src="../images/2024-10-29/bug.png" width="120">

The engineers have settled on calling this error a "bug" after literally finding one causing an issue in their machine, and named the process of troubleshooting such errors as "debugging".

<hr>

## My Debugging Experience
My class took a break for a day on writing new code, and our instructor taught us to "debug" code. We were to **look for errors** in given code snippets, **correct** them, and **explain** the process. And it was more than the code itself.

![Correcting this code to limit attempts to 3](/images/2024-10-29/limitAttempt.png "You don't get much tries on this one.")

![The call stack returning the error](/images/2024-10-29/callStack.png "Whoops I've made a spelling error with a variable!")

In Visual Studio Code, a `"Run and Debug"` feature has been added to the editor. This feature allows for **running a file and squashing bugs** out of the way. I never really knew this would've come in handy. But it truly did, and that's what we used for the day's lesson.

### The Debugging Process

We were given some code snippets in a Google doc. We were to paste each of them one at a time into the editor, and then run the debugger. We learned about **breakpoints**, which is a set point that the debugger will stop at. Since we were coding in `Python`, we used the `Python debugger` in particular for this assignment.

![Local variables and the debugger](/images/2024-10-29/varsDebug.png "See what you can do with the debugger.")

`Python Debugger: Debug Python File` was our run option. We would run that and see all the variables tha have been ran on the side bar. We would understand the results after a certain number of iterations and what happens if we changed them.

We would also find more detailed error messages for things that didn't run correctly. Though we didn't understand the exact jargon, we were able to figure out what went wrong. Then we would easily get rid of that pesky bug. The debugger is an easy way for good riddance.

<hr>

### Debugging Task 1: Count how many spaces are in a given string

**Issue**: ```The output is the integer of what the count variable is set to. It is not outputting how many spaces are in the string because “if char” is equal to nothing.```

![Issue 1](/images/2024-10-29/issues/issue1.png "Something went wrong with counting here!")

**Solution**: ```Add a space in the if statement string to account for all the spaces in the string of the text variable.```

![Solution 1](/images/2024-10-29/solutions/solution1.png "Add that space to the if statement string")

<hr>

### Debugging Task 2: Determine if numbers 1 to *n* are even or odd

**Issue**: ```The input type is not set to “int” and the operator is incorrect. The input number n is not accounted for since it’s in a range.```

![Task 2](/images/2024-10-29/issues/issue2.png "A wrong input type...")

**Solution**: ```The input type will be an integer, therefore it will be int(input()). +1 will be appended to n to account for the inputted number. The operator will be changed from < to == to account for the even/odd remainder.```

![Solution 2](/images/2024-10-29/solutions/solution2.png "Turn it into an integer.")

<hr>

### Debugging Task 3: Calculate the factorial of a given number

**Issue**: ```The program cannot concatenate (link) a string to an integer, as coded in the print statement. The num should also be < 0 to block out all negatives.```

![Issue 3](/images/2024-10-29/issues/issue3.png "Can't mix a string and an integer!")

**Solution**: ```Convert the print statement. Use f-strings for smooth formatting and integration of various data types. Change -1 to 0.```

![Solution 3](/images/2024-10-29/solutions/solution3.png "F-strings make our lives easier.")

<hr>

### Debugging Task 4: Ask user to enter the correct password but only give them 3 attempts

**Issue**: ```The if password statement was set to the incorrect string. Attempts were also set to be > 3, so it would still run after the third attempt, but it must be at 3 attempts to break. The program doesn’t exit and loops upon correct entry.```

![Issue 4](/images/2024-10-29/issues/issue4.png "If password is incorrect, it's still incorrect!")

**Solution:** ```Set if password equal to the variable correct_password, break the program upon the correct entry, and set attempts == 3 so that the program breaks after 3 incorrect attempts.```

![Solution 4](/images/2024-10-29/solutions/solution4.png "We had to put the correct password ourselves.")

<hr>

## Can you "Debug" you Life?

Your life isn't a computer or a program, however, similar to how **debugging**, there *is* a way you can. What I've found out was that not everything will turn out perfectly on the first try. It takes multiple attempts and reviews to perfect any experience.

When you try something, it won't work flawlessly at first. You have to get used to the antics and find out what went wrong. Once you do so, understand why it happened and mitigate that issue. It will be better than it was before. Many things are based on **trial and error**. It's a great way of understanding issues.

If you move on to a more advanced step, consider all of the problem-solving methods you have used in previous encounters, and the first try later will be even better than the very first time.

![Cool Thumbs Up with Sunglasses](/images/2024-10-29/thumpSunglass.jpg "Very cool to follow these steps!")