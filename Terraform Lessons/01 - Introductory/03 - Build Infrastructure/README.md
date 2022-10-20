# 03 - Build Infrastructure

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

## Assignment for lesson 3:
1. You should be working within your AIRS subscription or your personal Visual Studio Subscription
   1. use `az account show`
2. Given the file `example.tf`, proceed with the following tasks:
   1. Find the terraform command to run before building infrastructure (HINT: Initialize is the keyword here)
   2. Run that command - it is okay if you do not understand what is going on
   3. The file looks a bit messy, find the terraform command to format and run it
   4. Now we need to ensure the file is written correct, find the terraform command to validate the configuration
   5. Before we deploy, it's always a good idea to see a plan of what will be deployed - find the terraform command to do so
   6. Now find the terraform command to deploy what is in `example.tf`
   7. After validating that the resources, let's clean up. Find the terraform command to destroy resources
      1. View the output given from the command and only type in yes after validating that those are the resources you want to destroy
   8. After reviewing item task 3, delete all files and directories except for `example.tf` and `README.md`
3. After deployment, you will notice a few files/directories created, namely:
   1. `.terraform`
      1. This directory is simply a local cache where Terraform keeps some files so that it can run the operations needed
      2. In this case, it contains the provider 'azurerm' so that it knows how to interact with Azure
      3. This is only a basic explanation of .terraform - it is highly recommended to do additional reading if it is not clear
   2. `terraform.tfstate`
      1. This information is CRITICAL to Terraform, and should be treated as a secret
      2. If you click to review its contents, you can see that it contains information about the resources deployed
         1. This is how Terraform knows what is currently existing, and how it knows what to destroy
   3. `.terraform.lock.hcl`
      1. As noted in the file name, this is a dependency lock file that belongs to the configuration as a whole
      2. Terraform creates it and expects to find it in your working directory when you run Terraform
      3. Terraform automatically creates or updates this when you initialize
      4. You SHOULD include this file in your version control so you can discuss potential changes to your external dependencies via code review
4. It is a lot of information to take in all at once, but if you do not understand, do not worry - focus on the tasks performed in task 2