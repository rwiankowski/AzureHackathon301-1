# Challenge 1

## Part A

Objectives:

* Create a Virtual Machine
* Create a Key Vault
* Store a secret in the Key Vault
* Log into the Virtual Machine interactively
* Use a command line tool to retrieve the secret from the Key Vault

Tips:

* make sure the name of the secret is "secret" - it will be handy for Part B

## Part B

Objectives:

* Deploy the application which can be found in the "Application" folder to the VM deployed in Part A
* Configure the application to retrieve the secret  created in Part A

Tips:

* The application is .NET Core so make sure that you install the .NET CORE SDK 2.2 on the VM
* Make sure the application isn't using your security context
