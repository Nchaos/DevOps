# 04 - Change Infrastructure

The purpose for this lesson is to get you at an intermediate level of understanding about PowerShell. 

A few things to note:
1. This assignment, and future assignments will contain a few tasks that will outline the goal of the assignment.
2. You will be expected to use outside help (Google, Bing, AskJeeves, StackOverflow, etc.), PowerShell's built in "Get-Help" or Get-Command", or any method you can think of.
3. Always feel free to reach out to a team member if something does not make sense.
4. Feedback is always encouraged!
5. Try not to copy and paste code snippets, type it out to build muscle memory!

## Pre-Requisites
1. Make sure you have your AIRS subscription setup or you can choose to use your Visual Studio Subscription from Microsoft
2. Make sure you have AzCLI installed
3. Visual Studio Code
   1. ***RECOMMENDED*** - Terraform extension by HashiCorp

## Assignment for lesson 4:
1. You should be working within your AIRS subscription or your personal Visual Studio Subscription
   1. use `az account show`
2. Given the file `example.tf`, deploy it, but do not destroy it afterwards - remember the commands from the previous lesson!
3. Now, go to `example.tf` and change the `name` of the resource `azurerm_resource_group` to `example-resource-group-2`
   1. Don't forget to save the file after making the changes!
4. Now run `terraform plan` and notice the output
   1. You will see that the plan states that the existing resource will be replaced because we are changing the name
   2. This goes back to the `terraform.tfstate` file - because we have an existing state from the first deployment in task 1, but changed the infrastructure, Terraform will try its best to change the infrastructure without having to destroy it, but things such as a name change require deletion
5. Go ahead and run `terraform apply` to see the changes happen in real time
   1. Review the changes Terraform is doing - in a nutshell
      1. It is reviewing the `terraform.tfstate` file
      2. Since there was a change in `example.tf` that does not match up to what is in the state, Terraform is going to go with the configuration in `example.tf`
      3. Terraform deletes the existing resource
      4. Terraform replaces the resource group with the new name
6. Run the `terraform destroy` command and review the output - only enter `yes` if it matches up to what you deployed
7. Remove all files and directories except `example.tf` and `README.md`