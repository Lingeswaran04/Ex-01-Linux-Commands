# Ex-01-Linux-Commands
# Name: LINGESWARAN K
# Reg no: 212222110022

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
![WhatsApp Image 2025-09-14 at 21 15 32_4a5b250b](https://github.com/user-attachments/assets/6813aff1-ab93-46b2-ac4f-2eb6e8f8d5f5)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![WhatsApp Image 2025-09-14 at 21 15 33_4f12f17d](https://github.com/user-attachments/assets/d011d328-bfdb-40b8-9d7c-e6f81ef6fe68)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![WhatsApp Image 2025-09-14 at 21 16 08_83504c9c](https://github.com/user-attachments/assets/8927416e-dbf3-44a5-a08e-63e0c0394447)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![WhatsApp Image 2025-09-14 at 21 16 29_597a6926](https://github.com/user-attachments/assets/9b29cb6e-8360-42d8-be4e-827e6246c8cf)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![WhatsApp Image 2025-09-14 at 21 16 50_8bdfbd0a](https://github.com/user-attachments/assets/2dee7a72-2542-4115-8955-c8d8683a0c10)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![WhatsApp Image 2025-09-14 at 21 17 30_09c52d23](https://github.com/user-attachments/assets/8f65d4a9-9dea-43ef-a3c2-82fd32c65f44)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![WhatsApp Image 2025-09-14 at 21 18 21_5731187c](https://github.com/user-attachments/assets/b3916b88-b431-44de-9cd0-4ab890a514f1)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![WhatsApp Image 2025-09-14 at 21 21 36_0dd2290f](https://github.com/user-attachments/assets/8876d111-200d-464b-8138-198e9ae0f487)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="622" height="67" alt="image" src="https://github.com/user-attachments/assets/e4f77ef1-b467-49d7-b511-09318a189e6b" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
![WhatsApp Image 2025-09-14 at 21 22 41_8f6699a4](https://github.com/user-attachments/assets/5a35f54e-a942-4955-b237-b21e8bbb17dd)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="684" height="166" alt="image" src="https://github.com/user-attachments/assets/782452c3-b694-4db3-9654-6d25319bac8a" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![WhatsApp Image 2025-09-14 at 21 24 07_03b7b023](https://github.com/user-attachments/assets/7fdf65cc-b698-44d5-a217-9674f632341c)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![WhatsApp Image 2025-09-14 at 21 25 05_d8d663f5](https://github.com/user-attachments/assets/f49ff238-ec97-4859-92f5-f4c074f9a59a)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![WhatsApp Image 2025-09-14 at 21 25 49_57610ed9](https://github.com/user-attachments/assets/5d9d8984-8307-4e93-a06e-325767d6471b)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<img width="622" height="41" alt="image" src="https://github.com/user-attachments/assets/0eef1659-eda9-48a2-a481-d57c607b95f4" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="707" height="128" alt="image" src="https://github.com/user-attachments/assets/d5d90d8f-5fdc-4f31-aad0-ebfa9754d085" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="579" height="199" alt="image" src="https://github.com/user-attachments/assets/93b76bf9-4b6b-4c98-8298-74cfa0183654" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![WhatsApp Image 2025-09-14 at 21 26 52_29627af1](https://github.com/user-attachments/assets/4eaf4ea9-78bb-42ea-bd4d-1c6aa4466e67)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="874" height="178" alt="image" src="https://github.com/user-attachments/assets/59bd0a48-ad3e-41aa-afab-bb17e020f219" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![WhatsApp Image 2025-09-14 at 21 27 24_47342f44](https://github.com/user-attachments/assets/b05cad3e-ff1d-4ae5-9b78-74f6cea4218f)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![WhatsApp Image 2025-09-14 at 21 28 01_4c1688f0](https://github.com/user-attachments/assets/b3b144d5-162e-4707-be82-4e3a43d7e903)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
<img width="692" height="131" alt="image" src="https://github.com/user-attachments/assets/5217129f-7cb2-4f2f-8f6a-4d108c0f257e" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
![WhatsApp Image 2025-09-14 at 21 28 34_98cafae5](https://github.com/user-attachments/assets/03221314-77fb-439e-8194-c0d483705105)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![WhatsApp Image 2025-09-14 at 21 31 02_423258af](https://github.com/user-attachments/assets/25cf8cd6-a547-429b-b339-e46841fe524b)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
![WhatsApp Image 2025-09-14 at 21 30 13_a8ee941a](https://github.com/user-attachments/assets/1cfd676d-3b98-4280-b8e1-1f149c616460)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![WhatsApp Image 2025-09-14 at 21 29 05_4453f347](https://github.com/user-attachments/assets/02ef8438-da9c-4a72-b0d1-4291b7bc4e3b)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
