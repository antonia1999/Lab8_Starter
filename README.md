# Lab 8 - Starter

1) Where would you fit your automated tests in your Recipe project development pipeline?
   automation testing: "scripts are written to automatically test new and existing software based on certain events, i.e. code getting pushed to the remote repository, or test runs of the whole repo that are triggered nightly.

   1.Within a Github action that runs whenever code is pushed 
   2.Manually run them locally before pushing code
   3.Run them all after all development is completed

   --> Number one applies for our project. We would fit our automated tests within a Github action that runs whenever code is pushed so that we do not get struggles at the very end. 

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
   --> No, because end to end testing tries to replicate a user’s workflow from start to finish. Instead we would use Unit testing to check if a function is returning the correct output.
   
3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.
   --> No, we would not use a unit test to test the "message" feature of a message application because the feature allowing the user to write and send a message to another user is quiet a lot to be tested (a many big functions). Instead I would use End-to-end testing.

4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.
   --> Yes, I would use a unit test to test the “max message length” feature of a messaging application because the “max message length” feature prevents the user from typing more than 80 characters. This means that it is only a small part because the max length of no more than 80 characters is not very long/big.