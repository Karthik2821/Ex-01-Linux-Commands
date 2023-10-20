# Ex-01-Linux-Commands


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

 ![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/db213581-7fdb-46c0-8001-e217b6c55407)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/42438692-2330-4e82-9198-47fe5a6ff3ff)

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/a98e26dd-fa68-47c9-9113-8882e91f46f4)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/0f36d663-c94d-459f-83fc-b8c62d741942)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/736202ad-8c1a-4437-8e6d-89f3a0cc5bea)

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/5a703027-9a1b-4998-9689-c14a58e7e31b)

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/45063939-93cb-42c1-a75a-04f1c0300325)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/b230d99c-bb2d-4d3c-9597-9bcd46a95f64)

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/f30c741f-ddc1-4f67-972b-8ab1d3d4b5d7)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/78f52fe6-68aa-4f73-ba0e-ca5c910158d7)
 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/936580c5-1d0d-4f4c-8030-90669a80af93)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/1c565e49-14a5-4ce0-a16e-8715cf86deee)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/4dfc81ac-22cd-4704-adea-8d670321592c)


### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/e6d52575-e9f1-42e4-82b6-17da605e114d)

### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/7ffab076-997c-41e4-9e4d-025dcd65361f)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/ffdcb371-dc5d-4052-9228-6535daa9958a)


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


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/3ca6aaf8-ceda-4a25-8670-8b5280fc851e)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/c85e178c-f40e-4f86-b21c-15f409a3aa05)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/0c95f98e-e5b2-4e27-86cd-18df3cf3e2e6)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/4ed069ae-2970-4ad4-aa3a-12d1fc1afd9f)



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/dca0818e-a573-4331-915f-76995c61effa)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/8fd97167-bdf1-428e-a1ea-1c46c70a67d0)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/8498c7c2-5d2e-49cb-8bb2-3c8a4e863329)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/9f58775b-a77e-41f3-abfa-b12ac55df7ed)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


![image](https://github.com/Karthik2821/Ex-01-Linux-Commands/assets/134921933/a25f65cc-b75a-42b9-b9f8-fa7c3d3d3549)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![Uploading image.png…]()


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”























## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
