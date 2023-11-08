# seng-3000-assignment-2AA
Assignment 2 - Authentication and Authorization

Authentication and Authorization

The last few weeks we have focused on Authentication and Authorization by using a JWT bearer token.

For this assignment, you need to demonstrate your ability to implement a JWT token service for authentication and then leverage the resulting JWT to authorize access to Web API endpoints. You are free to use any language, IDE, package, tools that you want. If you are using something different than what I'm demonstrating, I only ask that you provide the necessary instructions for me to run your code on my computer.

Requirements

Token Service

Must validate username/email address and a password from a user database table that contains hashed and salted passwords. Must have at least two users predefined in user table with different roles Role and username/email address must be included in JWT claims Must return an appropriate http status code if authentication failed Web API

Must perform the following JWT validations token has not been modified token has not expired token has valid audience token has valid issuer Must define at least two different authorization policies based on roles Must apply at least two different authorization policies on controllers/endpoint methods Must allow anonymous access to at least one endpoint method ReadMe.md

Must provide any special instructions if using different tools than what is presented in lectures Must provide two username/email address and password that have different roles for which authorization policies have been defined Document which endpoints have been provided that meet the Web API requirements above (authorization policies applied and anonymous access) Testing

Provide screenshot of successfully retrieving a token Provide screenshot of failing to retrieve a token Provide screenshot of decoded JWT by pasting your token into JWT.io website GIT

Initialize your code as a git repository Add an appropriate .gitignore file Stage and commit all code changes (It is your responsibility to confirm all your changes are committed) Place your .git file into a zip/compressed file and submit the zip file. Zip file should be named Assignment1_LastName_FirstName.zip. Instructions

You must follow instructions above (20 pts) A .gitignore file exclude files that should not be included in source control (e.g. for VS Code it would exclude things like .vscode, bin and obj folders). You can download/copy the contents of a git ignore for your IDE/language from github https://github.com/github/gitignoreLinks to an external site. Contents should be placed in a text file named .gitignore in the root folder of your git repository (same directory as the .git file).

With the exception of following instructions, each bullet point is worth 5 points. Following instructions is worth 20 points.

Only include your project/code in the zip file. Do not zip screenshots or other files submitted. I will review this content in Canvas. Your code is the only thing I should have to download to grade it.

You may use Assignment 1 as a starting point for Assignment 2 if you want.
