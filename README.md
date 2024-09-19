java c
DS2000 
Fall 2024 
Homework 1 
Assigned: September 13, 2024
Deadline: September 20, 2024 at 9pm easternSubmit each program as a .py file in gradescope (filenames are specified below). You may submit multiple times right up until the deadline. You may submit up to 48 hours late for no penalty. This policy exists for those times you're having a tough week, are feeling sick, or are falling behind in your work; we won't make any exceptions to this policy. You will have an opportunity at the end of the semester to submit one of homeworks 1-5 for a new grade. Your solution will be graded according to the DS2000 general rubric and style. guide. You may not use conditionals or loops on this homework. The entire assignment can be accomplished with material we’ve covered in lecture. Style. Guide Focus (pay attention to these items in particular for this Homework, but the entire style guide will be used during grading, so please make sure you review it!) ● def main is used to organize code ● Constants are used for non-changing values; they are named in all caps and initialized above main ● Numerical values are not rounded during computation; they are rounded only for the user’s sake The 30-minute Guideline If you get stuck on a homework problem, come by office hours, post on Piazza, or take a break! We recommend you spend about 30 minutes trying to figure out a problem -- enough time that you can try a few things to get unstuck, but not SO much time that you’re banging your head against the wall. Try for 30 minutes, then take a break, take a walk, and/or ask us. :) Review the Autograder Output When you submit your solution, gradescope will run your code and print out the results so you can see   what we’ll see when grading. Look at this output! It serves as a sanity-check to make sure your code    produces what you wanted; if it doesn’t, you can make revisions and resubmit up until the deadline. See the Gradescope FAQ to troubleshoot. It’s fine to work with friends and share ideas with each other; it is not fine to share code. Do not show your code to classmates or post code on piazza. 
Problem 1 - Every Vote Counts 
Filename: elections.py
Prompt the user for, in this order:
● A U.S. state (a string).
●   How many people in this state voted in the November 2020 election? (This value should be an int and should not be abbreviated to thousands; find examples here.)
●   What percentage of the voting population does that represent? (This value should be a float in the range 0-100; find examples here.)
Using this information, compute and report the answers to the following questions. Round to a reasonable number of decimal places when reporting your results.
● How many people were eligible to vote in this state in 2020?
● How many people who were eligible to vote in 2020 did not?
●   It is hard to predict voter turnout in the coming election, but let’s say it decreases. If the number of 2020 voters in this state decreases by 3.2%, how many people will vote in this state in 2024?
●   There are 21,033 undergraduate students at Northeastern. If they all vote in this state in 2024, what percent of the vote would they collectively contribute?For full credit under documentation, write a test case in a comment at the top ofyour file, something like this but with your own examples. Do this before you start coding so you know代 写DS2000 Fall 2024 Homework 1Python
代做程序编程语言 your program works! It's  okay if the format ofyour test case is different from your program's output.

Here’s an example of what happens when I run my program. (Your output doesn’t need to look exactly the same, but DO make sure your prompts are in the same order so that the autograder works):

Problem 2 - Olympic Year Filename: olympics.py
American runners Gabby Thomas (she/her), Nikki Hiltz (they/them), and Cole Hocker (he/him) all put on a great showing at the 2024 Olympic Games. Let’s figure out how fast they really are. :)
Prompt the user for, in this order:
● The name of an athlete (string).
● The distance of their race, in meters (int).
● Their time in the race, given in total seconds (float).
Using this information, compute and report the answers to the following questions:
● How many laps of the track was their race? (There are 400 meters per lap.)
● How many minutes and seconds was their race (note that minutes might be zero!)?
● What was their pace per lap, in minutes and seconds?
● What was their pace per mile, in minutes and seconds? (There are 1609 meters in a mile.)
For full credit under documentation, write two test cases in a comment at the top ofyour file, something  like this but with your own examples. Do this before you start coding so you know your program works!

Here’s an example of what happens when we run our program (yours doesn’t need to be exactly the same, but DO keep the prompts in the same order for the autograder):

Problem 3 - That Brand Life 
Filename (code): influencer.py
Filenames (plot): influencer.png
Profs. Felix and Laney have decided to leave academia behind and become influencers on social media, under the brand FnL. They’ll be huge. In September 2024, FnL has 100 followers, but we expect a huge increase almost immediately. We assume that 5% of followers view any given post, 2.7% like it, and .97% comment on it.
The user for your Python program is a brand. Prompt the user for, in this order (all floats):
● How much will you pay per-view, for one post?
● How much will you pay per-like, for one post?
● How much will you pay per-comment, for one post?
Use the above information to compute (no need to print, except for testing!):
● How much money will one post generate for FnL, assuming we have 100 followers?
● How much money does one post generate, per follower?
● How many followers does FnL need to have to make $1,000 per post?
Create a scatterplot using plt.plot() where number of followers is on the x axis and per-post income is on the y axis. Your plot should have 4 separate points:
● Current per-post income for our starting point, September 2024 with 100 followers.
● Per-post income for October 2024, when our followers increase by 250%
● Per-post income for November 2024, when our followers increase by another 300%
● Per-post income when we reach our goal of $1,000 per post.
Save your plot as a .png file; do not submit screenshots. Make sure you review the style guide for the specific requirements that apply to all your plots in DS2000!
For full credit under the documentation category, write a test case in a comment at the top ofyour file,  like this but your own info. Do this before you start coding -- that way you know your program works!




         
加QQ：99515681  WX：codinghelp
