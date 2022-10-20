# 02 - First-Time Git Setup

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

## Assignment for lesson 2:
1. Before we are able to work in Git, we need to configure a few things:
   1. Username
   2. E-mail Address
2. This is critical because when Git uses this information and is immutably baked into the commits you start working on
   1. Configure your user name and e-mail by running the following
      1. `git config --global user.name "First-Name Last-Name"`
      2. `git config --global user.email "Your email address here"`
         1. Example:
            1. `git config --global user.name "John Doe"`
            2. `git config --global user.email "johndoe@example.com"`