# 02 - Setting up Remote State
=============================

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
1. You should be working within your AIRS subscription or your personal Visual Studio Subscription
   1. use `az account show`
2. Create the following file
   1. `main.tf`
3. Utilize the `terraform` block in order to setup the azurerm backend
   1. HINT: https://docs.microsoft.com/en-us/azure/developer/terraform/store-state-in-azure-storage
   2. HINT: Skim through the page mentioned above, you will notice that you will need to create some pre-requisite resources in the Azure portal
4. Create a resource group
5. Ensure that your `.tfstate` is currently hosted in Azure