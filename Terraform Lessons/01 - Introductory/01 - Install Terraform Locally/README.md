# 01 - Install Terraform Locally

The purpose for this lesson is to get you at an intermediate level of understanding about Terraform. 

A few things to note:
1. This assignment, and future assignments will contain a few tasks that will outline the goal of the assignment.
2. You will be expected to use outside help (Google, Bing, AskJeeves, StackOverflow, etc.), HashiCorps Terraform documentation, or any method you can think of.
3. Always feel free to reach out to a team member if something does not make sense.
4. Feedback is always encouraged!
5. Try not to copy and paste code snippets, type it out to build muscle memory!

## Pre-Requisites
1. Make sure you have your AIRS subscription setup or you can choose to use your Visual Studio Subscription from Microsoft
2. Make sure you have AzCLI installed
3. Visual Studio Code
   1. ***RECOMMENDED*** - Terraform extension by HashiCorp

## Assignment for lesson 1:
1. Navigate to the Terraform download site - [Terraform Download](https://releases.hashicorp.com/terraform/)
2. Download Terraform version 0.14.5 (we will be using this version exclusively for this training)
3. Move the Terraform executable to a directory of your choosing (or create one - I have a C:\bin directory where I have my executable)
4. Setup your path to include the directory where your terraform executable is (for Windows)
   - Here is an article that describes how to set it up [Setup Terraform Path](https://stackoverflow.com/questions/1618280/where-can-i-set-path-to-make-exe-on-windows)
   - You can set it as either a system variable or an user variable
5. Open up a new console and run the command 'terraform -v'
   - If your path is setup correctly, you should receive output of the Terraform version you have installed