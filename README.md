## Two Activities Homework - Solution Code 

The TwoActivities homework app is a basic app with a Toast button that launches a new Activity to display the word "Hello!" and the current count. It change the text on the Toast button to Say Hello.

## Pre-requisites

To execute this app you should be familiar with:
Creating and running apps in Android Studio.

## Getting Started

Download and open the app in Android Studio.

## The Homework app should contain the following features:

<li>It displays the Say Hello button instead of the Toast button.

<li>The second Activity starts when the Say Hello button is pressed, and it displays the message "Hello!" and the current count from MainActivity.

<li>The second Activity should contains two TextView elements, one with the string "Hello!" and the second with the count.

<li>It includes an implementation of a click handler method for the Say Hello button (in MainActivity).

<li>It includes an implementation of the onCreate() method for the second Activity and updates the count TextView with the count from MainActivity.

## Result 

#### TwoActivities Homework Screenshots.


![](TwoActivities Assignment1.png)

![](TwoActivities Assignment2.png)



## Some Basic Git Commands

### git init

This command is used to start a new repository.

<li>Usage: git init [repository name]
 
### git clone

This command is used to obtain a repository from an existing URL.
<li>Usage: git clone [url]

### git add

This command adds a file to the staging area.

<li>Usage: git add [file].

This command adds one or more to the staging area.
<li>Usage: git add 


### git commit

This command records the file permanently in the version history.

<li>Usage: git commit -m “[ Type in the commit message]”

This command commits any files you have added with the git add command and also commits any files you have changed.

<li>Usage: git commit -a  

 
### git branch

This command lists all the local branches in the current repository.

<li>Usage: git branch 

This command creates a new branch.

<li>Usage: git branch [branch name] 

This command deletes the feature branch.

<li>Usage: git branch -d [branch name]


### git checkout
This command is used to switch from one branch to another.

<li>Usage: git checkout [branch name] 

This command creates a new branch and also switches to it.

<li>Usage: git checkout -b [branch name]
 

### git push

This command sends the committed changes of master branch to your remote repository.

<li>Usage: git push [variable name] master
 
This command sends the branch commits to your remote repository.

<li>Usage: git push [variable name] [branch] 

This command pushes all branches to your remote repository.

<li>Usage: git push –all [variable name]

This command deletes a branch on your remote repository.

<li>Usage: git push [variable name] :[branch name] 
  

### git pull

This command fetches and merges changes on the remote server to your working directory.

<li>Usage: git pull [Repository Link]
