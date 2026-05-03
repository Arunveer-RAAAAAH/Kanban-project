As a new user, I need to create an account, so that I can access the platform.
Given the user is on the registration page
When they enter valid details and submit the form
Then their account should be created successfully

Given the user enters an already registered email
When they submit the form
Then an error message should be displayed
