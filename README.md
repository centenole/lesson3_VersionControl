# Project Name:  Lesson 3 Version Control


## Course Title:
Web Application Development

## Assignment Date:  
(September 29, 2017)

## Student Name:  
(Steven Centeno)

## Project Description:
(In this assignment I learned how to use Git for version control and group collaboration purposes.)

## View Project
https://centenole.github.io/lesson3_VersionControl/

## Lessons Learned in the Assignment:
1. (Briefly describe a lesson/concept learned in this lesson.)
Unlike other VCS', Git stores and updates information whenver a file is changed but also takes a "snapshots" of the files before the change is made. Why is this a good thing? Well, when working on huge projects or programs, being able to look back at how the program looked before someone made changes to it is very useful for finding bugs and errors, correcting mistakes, group collaborations etc.
2. (Briefly describe a lesson/concept learned in this lesson.)
Git and other VCS' can be very useful for big group projects. Lets say you want to make a massive fantasy role playing video game like Skyrim or something like that. From a programmer's perspective, that is an insane amount of work because of all the little things that make the game whole. Running maintenance on a game like this sounds like a nightmare, but with VCS' like Git, its easy to go back and forth to see what people have changed exactly where they changed them. Companies like apple and samsung use VCS' like Git to create proper software updates. It can even be used by freelance programmers to show their clients "Hey this is what I changed about this thing you had me fix. Here is the before and here is the after."
3. (Briefly describe a lesson/concept learned in this lesson.)
When importing the my lesson 3 page to Git, I was instructed to use a number of commands to link my Cloud9 files into Git. Before using code we had to link our Cloud9 account to our Git account. This was easy, as cloud9 gives you the option to do so in its settings. After doing that we copied an SSH key into Git that connect Cloud9 to the private Git Repository. Next we configured Git within Cloud9 and then moved the page files into the local repository using the following lines of code. 
$ git config --global user.name “Steven Centeno” 
$ git config --global user.email “sjc15d@my.fsu.edu”. 
$ git init 
$ git add . 
$ git commit -m ‘first commit for lesson 3’

