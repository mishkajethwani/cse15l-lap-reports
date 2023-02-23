# Researching Commands 

I decided to choose the command find and find 4 interesting command-line options to use with it. To do so, I asked chat gpt for suggestions. <br>
![Image](one.png)
I decided to use the the following four commands: <br>
1. "find /path/to/directory -size" <br> 
2. "find /path/to/directory -type" <br>
3. "find /path/to/directory -mtime" <br>
4. "find /path/to/directory -name" <br>

### SIZE 

To figure out how to use this command line option and for reference I used [this site](https://linuxconfig.org/how-to-use-find-command-to-search-for-files-based-on-file-size).<br>
To get files greater than or smaller than a certain size, this command is used. The command is  "find /path/to/directory -size" followed by a +/- sign and the size of the file. + is used to get files of sizes greater than the specified amount and - is used to get files smaller than the specified amount.<br>
For exmaple, In the first command I used *find * -size -10M*, which gave me all the files smaller than 10 MB.
![Image](two.png) <br> 
In the second example I used "find * -size +5M" which gave all the files that were bigger in size than 5MB, which didnt exsist so it displayed nothing.
![Image](three.png)<br> 

## TYPE

As reference, to understand how to use this particular command I used the following [resources](https://linuxize.com/post/how-to-find-files-in-linux-using-the-command-line/).<br>

This used to get particular types, such as f is used to get files and d is used to get directories. <br> 
Here, In the first example I used find * -type d to get all the directories.
![Image](four.png) <br> 
In the second example I used * -type d to get all the files. 
![Image](five.png) <br> 


## TIME

The resources I used for this are [here](https://www.geeksforgeeks.org/time-command-in-linux-with-examples/) and chatGPT.<br>

This is used to find files based on the time they were last modified or accessed usimg -mtime and -atime respectively. <br> 
For example, I used "find * -mtime +7" to get all the files that were modified more than 7 days ago.
![Image](six.png) <br> 
Next I used "find * -atime +8" to get all the files that were accessed more than 8 days ago. 
![Image](seven.png) <br> 

## NAME

To figure out how to use this command line option and for reference I used [this site](https://www.cyberciti.biz/faq/search-for-files-in-bash/).<br>

In this I used multiple command-line operators to do specific tasks. 
First, I used "find travel guides/berlitzl/ -name "*.txt" -delete" to delete all the .txt files in the berlitz one folder. This can be seen in the picture below, as I have displayed all the files before and after using the command using ls. 
![Image](eight.png) <br> 
Then, I used a command to cat the file "California-History" to display the contents of that file. 
![Image](nine.png) <br> 











