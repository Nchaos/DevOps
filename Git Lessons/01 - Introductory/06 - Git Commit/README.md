# 06 - Git Commit

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
3. It's recommended that you do the lessons via the Git CLI to understand what is going on, whereas using VS Code it's a simple click of a button, but you don't quite understand what's going on

## Assignment for lesson 6:
1. In the directory where you have setup a Git repository, create a new file named `commit` and add it to your staging area via `git add`
2. Once your file has been added to the staging area, you can now run `git commit` and you will be prompted to insert text
   1. If you are brought in a terminal, you will have to press "I" to begin typing.
   2. The window brought up should be asking for a "commit message", meaning that here you can specify what changes you have made. Keep it short and sweet to where someone can easily read your commit and understand what you've done.
   3. Once you have written you message in the terminal window, press ESC and type in ":wq"
3. In summary, we have covered the basic process when working with Git:
   1. Initializing a Repository / Cloning a Repository via `git init` or `git clone`
   2. Making modifications / creating new files
   3. Adding them to your local Git repository's staging area via `git add`
   4. Committing changes to your local repository via `git commit`
4. Now to piece all of these together, instead of running `git add` all the time, and especially with repositories with many files, you can utilize `git commit -a -m "commit message"` to knock out all of those steps in one command (always be aware of what you are commiting)
   1. The -a flag tells git to commit all changed files
   2. The -m flag allows you to specify the message with the commit instead of being brought to the terminal page
5. Keep in mind that this process is mostly interacting with your local repository - this will not push any changes up to any repositories. However, these steps are also used when pushing to a remote repository (which we will get into in future lessons)

**NOTE:** You can also use the VS Code source control tab to do all of this, however it is important to understand what VS Code is actually doing behind the scenes. 