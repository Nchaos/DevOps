# 07 - Query Data with Output Variables

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
2. In the `outputs.tf` file, crete outputs for the following values:
   1. Location
   2. ID
3. Use the official Terraform documentation for the azurerm_resource_group for reference. 
4. There is an example in the current `outputs.tf` that you can build off of.
5. After creating the required outputs, apply the terraform file then use the terraform command to show the outputs (you will need to find this).