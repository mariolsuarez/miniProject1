### Linux Basic Commands

In this tutorial you will learn basic commands that are very useful when
working in Linux.

1. cd -> **Change directory** This command helps you to change directory.
  - $cd <file name> will move you to the <name> directory
  - $cd .. this will bring you backwards one directory at a time
  - $cd ../.. this will bring you backwards two directory at a time
  - $cd ~ this will bring you back to Home.

2. mkdir -> **Make directory** This will allow you to create a new directory.
  - $mkdir <name> will create a directory called "<name>"
  - $mkdir -v <name1> <name2> will create the directories called "name1" and "name2"

3. cp -> **copy** This will make copies of files and directories
  - $cp <file you want to duplicate> <name of new file>

4. pwd -> **print working directory** -> This will let you see the path of the working directory starting from the root.
  - $pwd will display: /home/myName/myCurrentDirectory

5. mv -> **move** This will move one or more files or directories from one destination to another. Also, it changes the name of a file.
  - $mv <source> <destination>
  - $mv file1.txt file2.txt then the file1.txt will be renamed as file2.txt

6. rm -> **remove** This works as a delete for files or directories
  - $rm file1.txt  will erase file1
  - $rm file1.txt file2.txt  will erase file1.txt and file2.txt

7. history -> This will display a list of the executed commands in Linux
  - $history  will display the list of all the commands that had been used
  - $history 3  will display the last 3 commands

8. Home directory and ~ -> Home directory is the user's root of all its files and directories
  - the ~ (tilde) will serve as shortcut to get back to home in this way user@myHome:~/Desktop/file1/Alpha$ cd ~
  will bring you to:
  user@myHome:~$

9. file paths in Linux -> This will be like a map path, to know exactly how to get to a certain directory or file
  - if you type user@myHome:~$ cd /Desktop/file1/Alpha
  this will take you directly to user@myHome:~/Desktop/file1/Alpha

- Using the tab key to complete file paths -> This will help you to find the
names of the files or directories in the current Directory
  - user@myHome:~/Desktop$ cd f and you hit the Tab key i will display all the current files and directories that start with f, making it easier to finish typing, if there is only one file or directory it will autocomplete it for you.


- Using up and down arrow for history -> This will display all the last executed commands in the Linux. It makes it easier because sometimes we want to reuse the
commands and it saves time.
