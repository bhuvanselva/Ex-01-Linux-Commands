# Ex-01-Linux-Commands
Bhuvaneshwari .S


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 
![image](https://github.com/user-attachments/assets/40ead97c-366c-4e68-92bb-632b60f950a2)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/user-attachments/assets/0fedf398-445a-4fa6-83e9-ec094d8cefc3)




 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/user-attachments/assets/10189d3b-070b-4066-9682-52c27a23b8ee)




### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/user-attachments/assets/67835c10-0ee6-46ac-b918-23e171309588)






### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/user-attachments/assets/d976cb37-66d3-44d6-840f-e80045d88de7)




### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/user-attachments/assets/262e5a62-672e-4d10-a09d-6e1d4f1ef3f6)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/user-attachments/assets/f4694d23-3dc8-4502-a9cf-67159c2a4b09)





### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/user-attachments/assets/468ff4a4-bcc6-4f42-8023-67cdc6b337e3)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/user-attachments/assets/d5a041eb-eb52-4d39-a245-922774fde2e0)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/user-attachments/assets/fe781bbf-bd34-494b-a07d-ea4989218e6b)



 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/user-attachments/assets/f26ff7f4-edda-4e6d-8aaa-64423b7de714)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/user-attachments/assets/93263a4a-1d09-4c76-9a64-c9cb7d008960)




### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/user-attachments/assets/64c987e4-f3b9-4cb8-8042-65d37b98329d)



 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/user-attachments/assets/570d1f41-81d0-4f64-a1db-62e493da44bb)



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/user-attachments/assets/e2d7d497-1304-4da3-8762-3b7c7fcaa842)




### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/user-attachments/assets/ccc3b4a5-ccbb-4d30-942c-7d68ccb95234)




### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

![image](https://github.com/user-attachments/assets/b16559f3-7496-4ea1-80f5-3ba4a0800971)


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
```

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
```
![image](https://github.com/user-attachments/assets/d88b9618-4edb-4d1e-9214-a2be8c4eae3a)
```


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
```
![image](https://github.com/user-attachments/assets/e7191b17-98d0-417e-a256-2cef90960add)
```


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
```
![image](https://github.com/user-attachments/assets/997f4f84-c616-4670-849b-a0bf78e037c9)
```


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
```
![image](https://github.com/user-attachments/assets/96ab5479-2fb1-4e41-825d-32fe8764c2fb)
```


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
```
![image](https://github.com/user-attachments/assets/01838867-34f9-4a2b-8e4c-631476c11414)
```



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
```'
![image](https://github.com/user-attachments/assets/c33e1789-a28d-4b28-b349-2f145e945c02)
```


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
```
![image](https://github.com/user-attachments/assets/305d6abc-0a6e-4f1f-8932-ea94fc37d33b)
```


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
```

![image](https://github.com/user-attachments/assets/8c38e294-d4dd-4557-a835-577c29fed218)
```

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
```
![image](https://github.com/user-attachments/assets/c15ad050-605e-453e-a95b-a3dc3be73d04)
```

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
