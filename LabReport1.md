## Lab Report 1 - Remote Access and FileSystem (Week 1)

# Using command cd
*Example One:*
![Image](cd.png)
1. The working directory when this command was run was /home. 
2. We got this output because the command was able to run in the terminal and there were no errors.
   However, the directory was not changed by us putting in the cd command wwithout an arg.
3. This output is not an error because when we use cd without an argument it will go to the previous
   working directory. Because we were already in the home directory and there was no previous working
   directory. However, if we were in the directory /home/lecture1 and we used cd without an argumemnt,
   the directory would be changed back to /home.   

*Example Two:* 
![Image](cdWithArg.png)
1. The working directory when this command was run was /home when we ran cd
   with an argument.
2. We got this output because with the argument of lecture1 the directory was changed to
   /home/lecture1.
3. This output was not an error because the command effectively changed the directory based
   on the argument.
   
*Example Three:*
![Image](cdFile.png)
1. The working directory when this command was run was /home/lecture1.
2. We got this output because the cd command doesn't take in a file name to
   change the working directory.
3. This output was an error because the correct input was not given along with the cd command
   and it was unable to change the directory. Instead, if we are trying to access a certain file
   we should change the directory and use the ls or cat command depending on our intention. 

# Using command ls
*Example One:*
![Image](ls.png)
1. The working directory when the ls command was run is /home.
2. We got the output "lecture1" because this is in the content of the /home directory
   and ls lists the working directory's files and directories.
3. This was not an error because the ls command gave the correct output when we ran
   it in the terminal.

*Example Two:*
![Image](lsWithArg.png)
1. The working directory when this command was run in the terminal
   was /home. 
2. We got this output because when we put ls into the terminal when the working directory
   was /lecture1 it outputs all the files and directories within this directory. So, this is
   why it outputs "Hello.class  Hello.java  messages  README" into the terminal.
3. This was not an error because the ls command effectively fulfilled its purpose and outputted
   the content of the working directory.

*Example Three:*
![Image](lsWithFile.png)
1. The working directory when this command was run was /home/lecture1/messages.
2. We got this output because ls listed the content of the file we entered. 
3. This was not an error because the ls command was able to execute properly. 


# Using command cat
*Example One:*
![Image](cat.png)
1. The working directory when we ran this command was /home.
2. When we ran the cat command in the terminal it kept infinitly running because it did
   not receive any input. So we got the output of nothing because the terminal was still 
   waiting for an input. To stop this I used the ctrl+c command to force a stop.
3. This was an error because this is what happens when we enter cat into the terminal
   without any arguments. 

*Example Two:* 
![Image](catWithArg.png)
1. The working directory when we ran this command was /home.
2. We got this output because when we input "cat lecture1" into the terminal the cat
   command reads the the input and will output the file's content.
3. This was an error because the cat command did not tell us the contnts of the files. 

*Example Three:*
![Image](catFile.png)
1. The working directory when we ran this command was /home/lecture1/messages.
2. We got this output because we inputed the file en-us.txt into the terminal and
   the cat command outputed it's contents which were "Hello world!"
3. This was not an error because the cat command executed properly and displayed what it was
   meant to. 

