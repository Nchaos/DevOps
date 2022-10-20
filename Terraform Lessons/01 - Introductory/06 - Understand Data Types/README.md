# 06 - Understand Data Types

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

## Assignment for lesson 5:
1. You should be working within your AIRS subscription or your personal Visual Studio Subscription
   1. use `az account show`
2. In the `variables.tf` file, create the following:
   1. A variable named `subnets` with a data type of list. Default value should be "172.0.1.0/24" and "172.0.2.0/24". Be sure to include a description as well.
   2. A variable named `name` with a data type of string. Default value should be "subnet". Be sure to include a description as well.
   3. A variable named `retention_days` with a data type of number. Default value should be "5". Be sure to include a description as well.
   4. A variable named `enabled` with a data type of boolean. Default value should be "true". Be sure to include a description as well
   5. A variable named `location` with a data type of map. Default value should be below. Be sure to include a description as well.
      1. subnet1 = 172.0.1.0/24
      2. subnet2 = 172.0.1.0/24