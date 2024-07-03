Q1. List three Linux Distributions
1-	Ubuntu
2-	Red hat
3-	Kali

Q2. From the slides what is the man command used for?
	man command is a Help command that provides short reference manuals for External commands 
and it is organized into sections
1-	For user commands 
2-	For system call

 ![image](https://github.com/luluehab/Embedded-Linux/assets/167600614/56593fe6-5067-43d1-8b27-35ce4c4b62df)

 if i don't know the command I can use
 $man –k

![image-1](https://github.com/luluehab/Embedded-Linux/assets/167600614/1cd21260-761e-4f54-b99b-c8ee785477a4)



Q3. What is the difference between rm and rmdir using man command?
1-	rm
to remove file or directory 
to remove file 
$rm

To remove directory recursively  
$rm –r
Or 
$rm –R 

2-	rmdir
to remove Empty directory 

![image-2](https://github.com/luluehab/Embedded-Linux/assets/167600614/9460b8fe-84c3-438c-97ee-46a3dabae5b4)



Q4. Create the following hierarchy under your home directory:
![image-3](https://github.com/luluehab/Embedded-Linux/assets/167600614/86a4f6ec-e5fc-46be-acbb-43aa1fe0975d)


![image-4](https://github.com/luluehab/Embedded-Linux/assets/167600614/38fbf7c5-b998-4e7c-ba85-98161f04ac44)




 a.	Remove dir11 with rmdir in one-step. What did you notice? And how did you overcome that?
rmdir: failed to remove ‘Directory’: Directory not empty
       the rm -r command deletes non-empty directories

![image-5](https://github.com/luluehab/Embedded-Linux/assets/167600614/63143f26-1ce4-450e-bbf7-49fb33aaebc2)


 b.	Then remove OldFiles using rmdir –p command. State what happened to the hierarchy (Note: you are in your home directory).

![image-6](https://github.com/luluehab/Embedded-Linux/assets/167600614/074ed13a-56b7-420a-96a6-106afda99ea6)


rmdir –p command  remove an empty subdirectory and its parent directory.
Nothing happened to the hierarchy.

c.	The output of the command pwd was /home/user. Write the absolute and relative path for the file mycv
Absolute
	/home/lulu/docs/mycv
              Relative path
		Docs/mycv
![image-7](https://github.com/luluehab/Embedded-Linux/assets/167600614/6493a01e-374a-4210-b19d-df918255a55c)



Q5. Copy the /etc/passwd file to your home directory making its name is mypasswd
cp /etc/passwd ~/mypasswd

![image-8](https://github.com/luluehab/Embedded-Linux/assets/167600614/4ff2a031-3b07-4730-8e64-3e3710bff381)



Q6. Rename this new file to be oldpasswd

![image-9](https://github.com/luluehab/Embedded-Linux/assets/167600614/dfba3cd2-2d6c-4886-876c-ba59758cabd7)




Q7. You are in /usr/bin, list four ways to go to your home directory 
cd 
cd ~ 
cd /home/lulu
cd $home

![image-10](https://github.com/luluehab/Embedded-Linux/assets/167600614/72268dbb-883f-46f0-826a-003daa6bbce8)



Q8. List Linux commands in /usr/bin that start with letter w
$ls /usr/bin/w*

![image-11](https://github.com/luluehab/Embedded-Linux/assets/167600614/92f043a9-8dab-4285-b122-3ce0f7a99364)


 

Q9. What command type are used for? (from the slide)
To know the type of command 
Alias or internal command(is the part of shell) or external command(exist as an executable file on the disk)
 
![image-12](https://github.com/luluehab/Embedded-Linux/assets/167600614/f96ee45b-5718-4bff-912c-1de64bc4b267)


Q10. Show 2 types of command file in /usr/bin that start with letter c 
$ls /usr/bin/c*
 
![image-13](https://github.com/luluehab/Embedded-Linux/assets/167600614/65cc3653-732a-4b03-8874-71c6bdb45fce)



Q11. Using man command find the command to read file. (Note: man take option) 
$ man –k read

![image-14](https://github.com/luluehab/Embedded-Linux/assets/167600614/f0e4dc47-6a8d-48c7-984f-f0a0f74427eb)


 
Q12. What is the usage of apropos command?

the apropos command and the man -k command serve similar purposes.
used to search the manual page names and descriptions for a keyword.
It is useful when i know what i want to do but iam not sure of the command.

![image-15](https://github.com/luluehab/Embedded-Linux/assets/167600614/c185e9ef-ac77-4634-8471-24bc5523cca4)


 





