# 02 - Setup your Terraform Environment with Azure

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

## Assignment for lesson 2:
1. Since we will be working with Azure and Terraform locally, we need to set up our environment locally
   1. Run `az login`
   2. A new window will pop-up - select the account which has the subscription you will want to work out of
   3. Run `az account set --subscription (name of your subscription, or the id)`
   4. Run `az account show` to validate that you are in the correct subscription
