# 05 - Git Diff

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

## Assignment for lesson 5:
1. In the directory where you have setup a Git repository, create a new file named `diff`, write some text, save it, and add it to your staging area via `git add` (do not commit anything).
2. Now, in the same `diff` file created, add some text to modify the text file and save it.
3. Run `git diff` and now you should see a comparison between what you intially created, and what you have modified (to get out of the terminal block that git diff takes you to, you can press q).
4. `git diff` is useful to see what has changed from your previous `git add` to now.
   1. If you are using VS Code, you can also use the source control tab and click on the file and it will also show you what has changed.
   2. Red text with "-" will indicate what you had prior, and the green text with "+" will indicate what you have changed