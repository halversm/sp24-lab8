# sp24-lab8
Materials for week 8 lab in CS-370, which includes Ch. 8 "A File Archiver" adapted from [Software Design by Example](https://third-bit.com/sdxpy/) by Greg Wilson.

_March 5, 2024_

Organization:
* SDX-ch10: The code files for the _SDX Ch. 10_ activity (as downloaded directly from the book website, unmodified) 

## Team Members for Part 1
Molly

## Team Roles for Part 1
Who will start out as
* DRIVER: Molly
* NAVIGATOR: Molly

You will switch halfway through the _SDX Ch. 9_ activity.

## Part 1 Documentation

Write your answers to the questions below.

* What were the main ideas from SDX chapter 10?
Version control and working with files.
* What questions did you have about the material in the chapters? What did you find confusing?
The reading was straight forward for the most part, but it was harder for me to wrap my head around manifest.

### Exercise 1: What familiar design pattern does this chapter employ?

Write your answers to the questions below.

* What design pattern do you think Wilson is using in section 10.4, and why?
Wilson seems to use inheritance since he derives a child class to archive things locally.

* How might you use this pattern to implement other kinds of archive features/properties?
Create new branches.


### Exercise 2: Applying the ideas in this chapter to your group project

Many of the concepts---and their implementations---in this chapter could be useful for your personal archive project. With your partner, discuss how you might extend the code from this chapter to be useful in your group project. Why and how might you do so?

Include a summary of your discussion here.
Iterative edits of the audio files. Simple version control system that allows a user to stage changes made to an audio file. Storing backups.

### Exercise 3: SDX section 10.6

Write a short summary of what you did (which exercises) below.
For sequencing backups, I created a new function to format the string filename. I then modified the function backup.