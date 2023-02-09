---
toc: true
layout: post
description: project planning CBPT
categories: [CollegeBoard, week 10]
title: Project Blog
---

# College board Performance task outline

### Materials

I will need to have a Performance task created that hits on all of the marks for the CB Performance task rubric. I will also need to record a video demonstrating program functionality. I also need to create a write up for my performance task that fulfills each of the points on the CB perofmrnace task. 

From the project I will use my own feature for my College Board performance task. this feature I will be taking for use in the performance task will be a program that gives the user a random fact/random word from a list, and allow users be tested on a random word's definition

### code 

The code will have a main function that creates a random word definition question by pulling from a question list, then it will compare a user's answer to the right answer and either output correct or not correct. There will also be a second function that just puts a random fact/word in the markdown fact/word table. although the 2nd function for random words/facts is done, creating the 2nd function that creates and tests the random queston is unfinished. Ideally, It will pull a random word question and then compare the user's answer to the correct answer, then output to the user whether or not they got the question right or wrong.

# College Board rubric (does it fulfil requirements?)

### Row 1
the program I am writing has an input (the answer to the questions) and output, as well as functionality and purpose. The purpose of the program is to entertain and educate the user by providing them with a cool fact by using the program

## Row 2
I do have a list that does store data and it is accessed by a function, and the data in it is used for the program for the better

## Row 3
the list I am using does manage complexity by storing the fact data and a solution without the list would be unecceccarily complicated, yet plausible. I'm thinking I will make a solution for not using list but if that is too hard I will explain why program can't be written without it.

## Row 4
I do have a function for calling random facts, but I plan on making a seperate function for questions that will include parameters and contribute to the program. EXPLICIT PARAMETERS IMPORTANT

UPDATE: have the function for generating questions now and it has an explicit parameter for the correct answer of the question.


## Row 5
My function will use sequencing by simply needing certain code parts to run before others, selection by using if else statements for right or wrong answer, and iteration to keep the question going until right answer is given.

UPDATE: I now have a function that includes sequencing, (the function), selection (if else statement for correct answer or not), and iteration (a while loop that checks if answer is right or wrong after 1st time question is wrong).

## Row 6
My testing will be passing in an incorrect answer and a correct answer and showing how the program reacts to those, may need to be change in future according to needs.


### video plan

for the video I plan to showcase the page refreshing and giving new facts/words, and then showcase adding a right and wrong answer to my question and showing how it tells you if you are right or wrong. 

here of the steps of the video:

1: open up the feature and press the button that activates the 1st function to show how I can pull random facts/words from my list. 

2: interact with the random question and type in a wrong answer, then press button to check answer and show getting it wrong.

3: finally, type in correct answer and show the program giving an output that shows I got the game right.