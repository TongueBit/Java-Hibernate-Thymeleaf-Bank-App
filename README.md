For this assignment you will be implementing some more of the Online Bank functionality.

The source code from which you should start building can be found via https://github.com/tp02ga/java-bootcamp/tree/master/Assignment13

Modify the /users endpoint
Once you have this code checked out, your task will be to enhance the /users endpoint to allow the userId values to be clickable.

When clicked on, this will send a GET request to the /users/{userId} endpoint

Here’s what the /users page should look like:

https://s3.amazonaws.com/javavideotutorials.net/exerciseFiles/Assignment13/Capture1.PNG


Note: The accounts should be clickable too, but you can do that at the end of the assignment once you’ve created the /users/{userId}/accounts/{accountId} endpoint.

 

Modify the /users/{userId} endpoint
On the /users/{userId} screen, you should add the address and account information and make the address information editable / savable.

This will be the toughest part of the assignment, as you’ll have three different relationships being displayed and managed on one screen.

Here’s what the /users/{userId} screen should look like:



When you click on the “Create New Bank Account” button, it should send a post to create a new bank account to the following url: /users/{userId}/accounts

 

Add the /users/{userId}/accounts/{accountId} endpoint
You will need to create a new account.html page where you’ll be able to modify the account’s name. Here’s what the screen should look like:


