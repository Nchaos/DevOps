# 01 - Creating Terraform Modules

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
2. Create the following files
   1. `main.tf`
   2. `outputs.tf`
   3. `variables.tf`
3. In the `main.tf` file, write Terraform code to create an Azure Resource Group
   1. Ensure you are using variables for all parameters
   2. NOTE: Refer to the Introductory lessons over Defining Input Variables
4. In the `variables.tf` file, create the necessary variables that you will use, something might be
   1. Location
   2. Name
5. In the `outputs.tf` file, create the outputs for ID and location
6. Create a new directory named `examples`
7. Create the following files in the `examples` directory
   1. `main.tf`
   2. `outputs.tf`
   3. `variables.tf`
8. In the `main.tf` file, use the module block to reference your newly created module
9. Copy and paste the data in your original `variables.tf` and put them into the new `variables.tf` that was created just now
10. Configure the `outputs.tf` to reference the ID and location
    1.  NOTE: You will need to lookup how module outputs are referenced