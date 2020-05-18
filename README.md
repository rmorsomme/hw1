# STA 323 / 523 :: Homework 1

## Introduction

>R, at its heart, is a functional language. This means that it has certain 
technical properties, but more importantly that it lends itself to a style of 
problem solving centred on functions.<br/><br/>
Hadley Wickham

<br/>

Watch the Homework 1 "getting started" video [here](https://warpwire.duke.edu/w/B8MDAA/).

## Tasks

#### Task 0

Briefly look over the below style guides and decide on a coding style that is
best for you. We won't be enforcing a specific style in this course, but be
consistent and loosely follow these guidelines.

- [Google’s R Style Guide](https://google.github.io/styleguide/Rguide.html)
- [Hadley's R Style Guide](http://r-pkgs.had.co.nz/style.html)

#### Task 1a

Write a function in R called `is_prime()` that performs a logical test
on if a positive integer is a prime number. Your function should have
one argument.

**Arguments**:
	
- `x` takes an atomic numeric vector of length one.

**Value**:

- Assuming a valid input is provided, the function should return a single 
  `TRUE` or `FALSE` value.

Make your function as robust as possible.
You may only use functions and operators available in `Base` R.

Please use code comments as you see fit. You do not need to document every line;
there is a write-up portion in Task 3.

#### Task 1b

Write a function in R called `is_anagram()` that performs a logical test
on if two words are anagrams. Your function should have
two arguments.

**Arguments**:
	
- `x` takes the first word as type character

- `y` takes the second word as type character

**Value**:

- Assuming valid inputs are provided, the function should return a single 
  `TRUE` or `FALSE` value.

Make your function as robust as possible. For simplicity, you may assume only
a single lower case word is input for each of `x` and `y`, and that 
both words are of the same length. Your function should handle
and return `TRUE` for "coronavirus" and "carnivorous". However, it does not
need to handle "Justin Timberlake" and "I'm a jerk but listen" (even those these
are anagrams of each other).

You may only use functions and operators available in `Base` R.

Please use code comments as you see fit. You do not need to document every line;
there is a write-up portion in Task 3.

*Hint*: `strsplit()`

#### Task 2

Perform testing and validation of your function. Try the test cases provided
and include additional cases to demonstrate the robustness of your functions.
This may inspire you to go back and refactor your code. 
Your functions should appropriately handle invalid inputs by providing an
informative error message. There will be a hidden set of test cases that will 
be used for grading purposes. The more cases your functions handle in an 
appropriate manner, the better your grade will be on this assignment.

#### Task 3

Include a brief write-up that describes how you approached the problem and 
constructed your solution for either Task 1a or Task 1b. Some things to think 
about and include:

- how did you handle possible invalid inputs;
- explain some of your code choices;
- is your function robust; and
- do you see any weaknesses with how you wrote your function;

Please keep the tasks separated in your R Markdown file.

## Essential details

#### Deadline and submission

**The deadline to submit Homework 1 is 11:59am ET on Wednesday, May 20.** Only
your final commit and code in the master branch will be graded. 
Do not forget to push your work to your assigned repository on GitHub before
the deadline.

#### Help

- Post your questions in the #hw1 channel on Slack. Explain your error / problem
  in as much detail as possible or give a reproducible example that generates 
  the same error. Make use of the code snippet option available in Slack.

- Visit the instructor or TAs in Zoom office hours.

- The instructor and TAs will not answer any questions within 6 hours of the
  deadline.

#### Academic integrity

This is an individual assignment. You may communicate with others in the
course, but you must write-up your own solution. As a reminder, any
code you use directly or as inspiration must be cited.

*Undergraduate:*

To uphold the Duke Community Standard:

- I will not lie, cheat, or steal in my academic endeavors;
- I will conduct myself honorably in all my endeavors; and
- I will act if the Standard is compromised.

*Graduate:*

Duke University is a community dedicated to scholarship, leadership, and 
service and to the principles of honesty, fairness, respect, and accountability.
Citizens of this community commit to reflect upon and uphold these principles in
all academic and non-academic endeavors, and to protect and promote a culture of
integrity. Cheating on exams and quizzes, plagiarism on homework assignments and
projects, lying about an illness or absence and other forms of academic 
dishonesty are a breach of trust with classmates and faculty, violate the Duke
Community Standard, and will not be tolerated. Such incidences will result in a 
0 grade for all parties involved as well as being reported to the University
Judicial Board. Additionally, there may be penalties to your final class grade.
Please review Duke’s Standards of Conduct.

#### Grading

| **Topic**             | **Points** |
|-----------------------|-----------:|
| Task 1a               |          6 |
| Task 1b               |          9 |
| Task 2                |          3 |
| Task 3                |          5 |
| 3 commits minimum     |          3 |
| Code style and format |          3 |
| Named R code chunks   |          1 |
| **Total**             |     **30** |

*Documents that fail to knit after minimal intervention will receive a 0*.

## References

1. Wickham, H. (2020). Introduction | Advanced R. Adv-r.hadley.nz.  
   https://adv-r.hadley.nz/fp.html