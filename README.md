
# Cloud Security Lab 1: Linux Commands Study

## Introduction to Linux

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

 <img width="409" height="79" alt="Screenshot 2025-09-08 200409" src="https://github.com/user-attachments/assets/497ab3b0-75ff-4d63-8e36-40b19642f229" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="261" height="66" alt="Screenshot 2025-09-08 200430" src="https://github.com/user-attachments/assets/5ddcf18d-ed5e-44b5-ab3e-b67205e952fe" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="542" height="129" alt="Screenshot 2025-09-08 200514" src="https://github.com/user-attachments/assets/fea8b559-40be-4a0e-8c6a-d8ae413a4ccf" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="639" height="135" alt="Screenshot 2025-09-08 200543" src="https://github.com/user-attachments/assets/0ff238e5-b03f-4b8a-8b26-36ecd8cb5abc" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="649" height="105" alt="Screenshot 2025-09-08 200612" src="https://github.com/user-attachments/assets/9ae7c927-5432-4689-b541-453afaed6b71" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="642" height="163" alt="Screenshot 2025-09-08 200712" src="https://github.com/user-attachments/assets/8e951345-1ca0-4c9a-a2cc-7d5f877c788a" />

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="645" height="110" alt="Screenshot 2025-09-08 200830" src="https://github.com/user-attachments/assets/6ee7a645-2bf7-4d61-ab21-cb9f86218687" />


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="635" height="212" alt="Screenshot 2025-09-08 200946" src="https://github.com/user-attachments/assets/1c01d2b9-ce89-424e-ab16-9f1c7ec2861a" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="654" height="57" alt="Screenshot 2025-09-08 201111" src="https://github.com/user-attachments/assets/a253884a-4bb3-410d-b332-7c696793e7e3" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="640" height="63" alt="Screenshot 2025-09-08 201155" src="https://github.com/user-attachments/assets/ee1b6eec-5748-40b7-a7aa-10e5ffeff4de" />


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="641" height="57" alt="Screenshot 2025-09-08 201518" src="https://github.com/user-attachments/assets/8636f17f-ff1f-4904-b075-93cdbd452316" />



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


<img width="308" height="215" alt="Screenshot 2025-09-08 201554" src="https://github.com/user-attachments/assets/56e9b6a4-f1bc-4af8-83e2-058b6ebf6d4f" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>


<img width="655" height="199" alt="Screenshot 2025-09-08 201619" src="https://github.com/user-attachments/assets/3bf72f2a-c7c2-42a9-b4d7-86cdf463f902" />


 ### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


<img width="630" height="118" alt="Screenshot 2025-09-08 201641" src="https://github.com/user-attachments/assets/2c48f7e8-14d8-4d73-a56e-1353597e4b1c" />



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


<img width="649" height="66" alt="Screenshot 2025-09-08 201711" src="https://github.com/user-attachments/assets/c2263b49-5de1-4d9a-9d3d-78907b5f6d80" />



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


<img width="645" height="93" alt="Screenshot 2025-09-08 201918" src="https://github.com/user-attachments/assets/919e227c-aa3d-431d-8071-db110d5d11f5" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>


<img width="649" height="164" alt="Screenshot 2025-09-08 201956" src="https://github.com/user-attachments/assets/c205dd76-0d72-44bb-80ac-214d52724a55" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c


<img width="649" height="374" alt="Screenshot 2025-09-08 202223" src="https://github.com/user-attachments/assets/c5e2b134-e42e-42de-a6cd-e548075bfa53" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name


<img width="631" height="245" alt="Screenshot 2025-09-08 202511" src="https://github.com/user-attachments/assets/85958b2c-5acc-4457-9cd8-a3ebcc0990e9" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


<img width="642" height="139" alt="Screenshot 2025-09-08 203421" src="https://github.com/user-attachments/assets/842e2215-b6b8-4dd8-af27-b1d88d603fb0" />



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="648" height="158" alt="Screenshot 2025-09-08 204024" src="https://github.com/user-attachments/assets/82a973a0-5b82-4cbd-8648-b1bddd90965e" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder


<img width="636" height="254" alt="Screenshot 2025-09-08 204101" src="https://github.com/user-attachments/assets/3dee2c47-c10f-4f23-87d3-cb91177f9a97" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


<img width="637" height="123" alt="Screenshot 2025-09-08 204234" src="https://github.com/user-attachments/assets/3258ca07-277f-4985-94e0-56e9ffaa7a5a" />



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


<img width="646" height="134" alt="Screenshot 2025-09-08 204435" src="https://github.com/user-attachments/assets/b5849c60-cf90-431e-85f2-0391eb3699cc" />



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


<img width="638" height="92" alt="Screenshot 2025-09-08 204533" src="https://github.com/user-attachments/assets/bc9f6066-0188-49cb-990d-ed94d6fd45e7" />


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


<img width="646" height="182" alt="Screenshot 2025-09-08 204658" src="https://github.com/user-attachments/assets/25c4a388-8098-4feb-af72-b95f4779713d" />



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


<img width="638" height="498" alt="Screenshot 2025-09-08 205917" src="https://github.com/user-attachments/assets/ffcfa0e9-2d40-4526-a0d8-408854992cf1" />



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


<img width="648" height="118" alt="Screenshot 2025-09-08 205346" src="https://github.com/user-attachments/assets/2f178e34-833a-457a-8a22-6d3b4c00eb77" />


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


<img width="635" height="244" alt="Screenshot 2025-09-08 205539" src="https://github.com/user-attachments/assets/cc013eaf-605d-494a-a21b-4563c56fb069" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


<img width="645" height="123" alt="Screenshot 2025-09-08 205859" src="https://github.com/user-attachments/assets/fa971031-1626-4697-9b91-e3bc5d97e524" />


## Result: 
The linux commands are successfully executed

