After forking the repository I started the timer, and follwed the following steps to make it more efficient. <br>
## Log into ieng6

The first step is to login to the your course specific ieng6 account. <br>
Instead of typing in ssh cs15lwi23apx@ieng6.ucsd.edu, I used the Cntrl-R which provided me with the command history where when I typed in "ssh" I got the entire command prompted and just had to press <enter>. 
 So, for logging into my ieng6 account, I used Cntrl-R, typed ssh and pressed <enter>.
  ![Image](one.png)
  
 ## Clone your fork of the repository from your Github account
 
  After this to clone the repository, Ater copying the link from the githuib site. 
 I again used Cntrl-R and got access to the command history where on typing "git c", I got the entire command and had to continue by pressing  <enter>.
  ![Image](two.png)
 
 ## Run the tests, demonstrating that they fail
 Again to run the tests I used Cntrl-R, typed out javac, which prompted me to javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java followed by <enter>. 
   ![Image](three.png)
 and now, for the second command did the same but typed out just java, which prompted me to java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore.
   ![Image](four.png)
 This saved much more time since otherwise I would have to go to the course website, look for theese and then copy-paste them.
 After executing theese tests, we can see that they failed.
  ![Image](five.png)
 
 ## Edit the code file to fix the failing test
   
  This showed one test failed, to fix the error I typed in nano ListExamples.java.
  I fixed the error, which was in the last while statement where I had to change index1 to index 2, then scrolling all the way up and typing "fixed" as a comment. 
  
 ## Run the tests, demonstrating that they now succeed

   To run the tests, I used upper arrow keys: 
  For the command javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java, I did <up><up><enter>
  and for, java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore I did,<up<up><up><enter>.
 Which now showed that the tests had passed. 
 
  To go back to the terminal I pressed, Cntrl-O <enter> Cntrl-X. 
  Then to submit and push I put the commands to add, commit and push in the same line to save time. I did this separating the commands by a semicolon. I used the Cntrl-R to type out the first one i.e git add and then typed out the commant for commit and push in the same line seprating them by semicolons.
 
  
  
  
  
  
  
  











