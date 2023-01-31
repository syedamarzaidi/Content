# Task 1

You are required to help a new Ubuntu user in performing Ubuntu commands. Mr. Tom is new Ubuntu user. He want guidance regarding basic Ubuntu utilities to perform following tasks:

1. Create a file named “19f-XXXX.txt”. File must contain at least 10 lines. 
2. Create another file named “your name.txt”. File must contain at least 10 lines. 
3.  Merge the data of both files. 
4. Redirect the output to a new file.
5. Display the first two lines of first file.
6. Display the last two lines of second file. 
7. Finds the string (your roll#) from the first file.
8.  Grant the execute permission of the second file to the group.
9.  Remove the write permission for the owner. 
10.  Now Mr. Tom suddenly lost the track of his current location. Help him find his location. 
11.  He wants the list of all files present on Desktop directory.
12. Now he wanted to create a folder of his personal files and pictures named as your roll#.
13. Display the current time.
14. He is done with the task and he is happy with your work. He want to display a thankyou message. 



### 1:

Now create a file using nano editor and add the text in file and using cat command to show the output of file on screen.

![VMware](img\1.png)

### 2:

Created another file with filename of my name and added 10 lines and using cat command to showing the output on screen.

![VMware](img\2.png)



### 3:

cat command is used to give output  and the redirection operator >> is used to append the output of amarZaidi.txt to the 2021CS64.txt file. so the file amarZaidi.txt is merged in 2021CS64.txt

![Ubuntu](img\mergeFile.png)



### 4:

Created another file newFile.txt and the output of 2021CS64.txt is redirected into newFile.txt

![Ubuntu](img\redirectNewFile.png)



### 5:

first two lines of 2021CS64.txt is shown on screen using head -2  

![Ubuntu](img\headlines.png)



### 6:

Last two lines of amarZaidi.txt is shown on screen using tail -2

![Ubuntu](img\taillines.png)



### 7:

The string "2021-CS-64" is searched in the file 2021CS64.txt using grep command the output of cat command is redirected to grep command.

![Ubuntu](img\rollNo.png)



### 8:

The execution permission to group on amarZaidi.txt using chmod g+x command.

![Ubuntu](img\executionGroup.png)



### 9:

write permission is removed from users on amarZaidi.txt using chmod u-w 

![Ubuntu](img\removeOwner.png)



### 10:

The current directory is shown to user because he lost his position.

![Ubuntu](img\pwd.png)



### 11:

All the files on Desktop directory is shown using ls command ../ is used because i am going back one time from my current position.

![Ubuntu](img\listDesk.png)



### 12:

Two directories personalFiles and pictures are created for user.

![Ubuntu](img\personal.png)



### 13:

current time is show using date other information like data is also shown.

![Ubuntu](img\time.png)





![Ubuntu](img\thankyou.png)





# Task 2

1. Create a file named “19f-XXXX_OS-lab_rules.txt” using Linux commands. The file must contain all lab rules covered in first lab.
2. You want to set the rights of created file to this (- rwx r-x r--). For these rights, you are required to convert the given rights in numeric format using binary number system procedure covered in lecture. Show complete working.
3.  Now use the derived number to change the permission of a file using chmod command. 
4.  Append the output of ls command to created file



### 1:

New file is created and the instructions from task1.txt is added in that file.

![Ubuntu](img\rules.png)



### 2:

numeric numbers are calculated for permission on file.

![Ubuntu](img\binary.png)



### 3:

required permissions are set on file

![Ubuntu](img\perm.png)



### 4:

the permissions of task2.txt is append in task2.txt file

![Ubuntu](img\append.png)

