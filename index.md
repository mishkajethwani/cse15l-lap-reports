The first step is to login to the your course specific ieng6 account. <br>
Instead of typing in ssh cs15lwi23apx@ieng6.ucsd.edu, I used the Cntrl-R which provided me with the command history where when I typed in "ssh" I got the entire command prompted and just had to press <enter>. 
 IMage
 So, for logging into my ieng6 account, I used Cntrl-R, typed ssh and pressed <enter>.
  
  After this to clone the repository, I again used Cntrl-R and got access to the command history where on typing "git c", I got the entire command nad had then press <enter>.
  
  To run the tests, I used upper arrow keys: 
  For the command javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java, I did <up><up><up><up><up><up><enter>
  and for, java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore I did,<up<up><up><up><up><up><enter>.
  
  This showed one test failed, to fix the error I typed in nano ListExamples.java.
  I fixed the error, which was in the last while statement where I had to change index1 to index 2, then scrolling all the way up and typing "fixed" as a comment. 
  
  To go back to the terminal I pressed, Cntrl-O <enter> Cntrl-X. 
  
  Then to sommit and push I put the commands to add, commit and push in the same line to save time. I did this separating the commands by a semicolon. 
  
  Then, to run the tests again I did <up><up><up><up><enter> follwed by <up><up><up><up><up><enter>.
  
 Which now showed that the tests had passed. 
  
  
  
  
  
  
  











