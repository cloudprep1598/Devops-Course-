# Devops-Course
# Technical guftagu 
# Lec on linux 1 


Linux flavors 
RHEL
Fedora
Debian
Ubuntu
Centos
Amazon Linux
Kali linux


OS used in two ways 
Command line interface
Graphical user interface

Linux is kernel not os
Linux is not a unix derivate and it was written from scratch
Linux distribution is the linux kernel and a collection of software that together create an os
Linux os is combination of linux kernel and GNU

Linux features 
Open source 
Secure
Simplified updates for all installed software
Light weight
Multiuser , Multitask
Multiple distribution like redhat , debian and fedora

File System hierarchy

/root
Home directory for root user


/home
Home directory for other user 


/boot
It contains bootable files for linux 

/etc
It contains all config files

/usr
By default software are installed in this directory 


/bin
It contains commands used by all users 

/sbin
It contains commands used by only root user 
/opt 
Optimal application software packages

/dev 
Essential devices files this includes terminal devices , usb  or any devices attached to the system 




How to create a fie 
Cat
Cat command is one of the universal tools , yet all it does is copy standard input to standard output
Create a file 
Concatenate file means more than one file into single file 
Copy the context of x into y
Tac 
Cat > file1

Touch command

Create an empty file 
Create multiple empty file 
Change the timestamp of a file 
Update only access time of file , modify time of file 

Time stamp 
Access time 
Last time when file was access 
Touch -a filename

Modify time 
Last time when the file was modified 
Touch -m filename


Change time 
Last time when file metadata was changed

vi/vim editor
A  programmer text editor
It can be used to edit all kinds of plain text ; it is specially useful for editing programs mainly used for unix programs
Vi is a standard whereas nano has to be available depending on the linux you use

Note : 
 :w  to save
:wq or :x to save and exit 
:q quit
:q! Force quit , no save 


Nano editor

# Practical 

<img width="600" height="476" alt="image" src="https://github.com/user-attachments/assets/e786c76e-c8cb-4864-a50d-a25dcc37074b" />




<img width="558" height="538" alt="image" src="https://github.com/user-attachments/assets/9125ca61-c79e-4fdf-bcee-27a994b2b9de" />





<img width="577" height="635" alt="image" src="https://github.com/user-attachments/assets/fec115a1-1237-482d-b271-7b51375ed5a6" />




<img width="505" height="610" alt="image" src="https://github.com/user-attachments/assets/1e6a1434-f1d4-4ba4-804d-51a58baf0761" />




How to create a directory 
Mkdir dir1 

Cd .. - go to parent directory



How to copy a file 
Cp source destination 

How to cut and paste file 
Mv source destination 

How to rename the file 
Mv file1 myfile        file1 is rename with myfile

How to create hidden files and directory 

Touch .file1    add - to create hidden file
Ls -a     to check all files including hidden also


How to remove directory ?

Rmdir directory name           - this cmd used to remove specified directory which ic empty

Rmdir -p directory name      -   this cmd remove both parents and child directory 

Rmdir -pv directory name    - this cmd removed all parent and subdirectory along with the verbrase

Rm -rf                              - remove even nonempty file and directory 

Rm -rp                           - remove nonempty directory including parent and subdirectory

Rm -r                           - remove empty directories



How to remove files 
Rm file1


Head filename 
Tail filename 
Less filename 
More filename


Lec 8 

Hostname   - give the name of the system 
Ifconfig        - give me the ip add
Hostname -i      give ip of that virtual machine
Cat  /etc/os-release    - to check current version of linux 


Yum install httpd 
Yum remove httpd
Yum update httpd 
Service httpd start
Service https stop 
Service httpd status 
Chkconfig httpd on 
Chkconfig httpd off
Which 
Whoami
Yum list installed                 - list of all installed applications 
Echo 

Echo “welcome”> file1
Echo “hi” >>file1 

Sudo apt update
Sudo apt install tree 

Lec 9 

Commands 

Useradd      username                                        - to create user (cat /etc/passwd)
Groupadd  groupname                                       - to create group (cat /etc/group)
Gpasswd -a  username groupname                     to add single user into the group 
Gpasswd -m user1 user2 user3  groupname     - add multiple user into the group

Ln -s filename1 softfile1
Ls -l 
Ln -s file1 softlinkfile1
Cat softlinkfile1


Ln - hardlink - create a backup of another link and create a copy of it
Ln file2 backupfile2 
Ln file2 hardlinkfile2


Tar - tar is an archiver used to combine multiple files into one 
Tar -cvf ( c for create , v for verbrase , f for forcefully ) tar filename filename 
Tar -cvf dirx.tar dirx

Gzip - gzip is a compression tool used to reduce the size of a file 

Wget - noninteractive network downloader
Wget <url>



# Access modes/permissions 

<img width="588" height="408" alt="image" src="https://github.com/user-attachments/assets/4af03817-7f79-498d-a8b1-f98f8b74f272" />


<img width="533" height="725" alt="image" src="https://github.com/user-attachments/assets/b93cbfa0-e25c-403c-9c0a-d8e4d8b4059d" />



Chown change the owner of the group 
Chown owner name filename  

Chgrp change the group of the file
Chgrp group name filename



<img width="462" height="756" alt="image" src="https://github.com/user-attachments/assets/4165584e-3423-4b99-9dd4-a7653757b0e3" />
