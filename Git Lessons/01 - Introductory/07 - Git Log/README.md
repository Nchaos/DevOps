# 07 - Git Log

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

## Assignment for lesson 7:
1. Clone this sample repository `git clone https://github.com/schacon/simplegit-progit`
2. In that new repository that was cloned on your desktop, run `git log`
   1. You will notice there is a few fields such as:
      1. commit
      2. Author
      3. Date
      4. commit message
   2. To navigate through the terminal, you can use the `Page Up` or `Page Down` key
   3. When you are finished navigating, you can press `Q` to get out `git log`
3. With this information, you will be able to do a few things, but notably, you can see the WHO made a commit and WHEN, and a commit message. This also goes back to why it's important to have commit messages that are short but understandable.

**NOTE:** For version that is easier to view, I personally like `git log --oneline` because it shortens everything to a single line. You will notice that some information is omitted (such as Author and Date), but you can at least see the commit messages and a portion of the commit hash.