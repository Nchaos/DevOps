# 05 - Define Input Variables

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
2. Notice in `example.tf`, we are hard-coding the name and location - this not best practice, so let's turn those fields into variables
3. Create a `variables.tf` file in the working directory
   1. In the `variables.tf` file, create two variables
      1. `name` with the value of `example-resource-group-var`
      2. `location` with the value of `eastus`
4. In the `example.tf` file - change the `name` and `location` fields to reference the variables
5. After creating the variables, go ahead and initialize your directory
   1. If you are receiving errors, review the message - Terraform is really good about telling you where an error is
6. Once initialized, run a plan to ensure that the name and location of the resource match your variables
7. You can choose to deploy the resources, or leave as is