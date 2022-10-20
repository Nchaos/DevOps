# 03 - Git Repositories

The purpose for this lesson is to get you at an introductory level of understanding about Git. 

A few things to note:
1. This assignment, and future assignments will contain a few tasks that will outline the goal of the assignment.
2. You will be expected to use outside help (Google, Bing, AskJeeves, StackOverflow, etc.), PowerShell's built in "Get-Help" or Get-Command", or any method you can think of.
3. Always feel free to reach out to a team member if something does not make sense.
4. Feedback is always encouraged!
5. Try not to copy and paste code snippets, type it out to build muscle memory!

## Pre-requisites:
1. You must have Git installed on your local machine
   1. [Git Installation](https://git-scm.com/downloads)
2. Your global user.name and user.email should be configured
   1. If not, see lesson 02 - First-Time Git Setup

## Assignment for lesson 3:
1. There are two ways of obtaining a Git Repository
   1. Creating a local directory and turning it into a Git repository
   2. Cloning an existing Git repository from somewhere else
2. This step refers to initializing a repository in an existing directory
   1. Create a directory that you would like to initialize as a Git repository
   2. On the command line, chang directory into the directory mentioned previously
   3. Run `git init`
      1. This will create a sub directory called `.git` (it may also be hidden) that contains all the necessary repository files
   4. Create a file in your directory named `test.txt` where you ran `git init` - you may notice that nothing is tracked, so you will have to add the file
   5. Run `git add test.txt` - this command will tell Git to track this file for changes
   6. Now, you can run `git commit -m "My first commit"` - this will put your changes in the local Git database
3. This step refers to cloning an existing repository:
   1. To clone an existing repository, you will have to utilize `git clone`
   2. If you have cloned the USDC DevOps repository, you may already be familiar with this process
   3. Run `git clone [Repository URL]` to get the existing repository
   4. When you clone a repository, all the files will be tracked and unmodified because Git just checked them out and you haven't edited anything