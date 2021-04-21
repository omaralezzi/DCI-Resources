# What is Bash?

- Bash is a Shell in form of a language, sorrownding the Kernel, that communicate with the Kernel. 
- Bash works on different OS based on Linux

## **Basic commands in the Terminal**

>#### **cd** - Change Directory

>#### **clear** - Clear screen

>#### **cp** (-l) - Copy a file - <br> 
>>`cp file newFolder/file`  
>>`cp filename.xxx -l a/b/c`- **_will send the file to the last directory_**

>#### **echo** - Write a phrase without any consecuence and can write a message inside a file without opening it   
>>`echo "hello" >> newfilecreated`

>#### **ll** - List all files with details + hidden files

>#### **ls (-alF)** - shows all files without details and no hidden files

>#### **mkdir (-p)** - Creates a new Directory (it creates a path of series folders) <br>
>>`mkdir -p a/b/c` - **_Will create 3 folders one inside the other_**
> - `~/folderyouarenow/a/b/c`
    
>>`mkdir -p a b c` - **_Will create them separately in the folder you are NOW_**<br>*

> - `~/folderyouarenow/a`  
> - `~/folderyouarenow/b`  
> - `~/folderyouarenow/c`

>#### **mv** - Moves files from folder to folder or renames files/folders
>>`mv fileyouchoose.xx ./a/b` - **_Will move that file into the b folder_**
>>`mv fileyouchoose.xx hereiputthenewname.xx` - **_Will change the name of the_** file


>#### **pwd** - (path working directory) - Shows the path you currently are

>#### **reboot (-f)** - Restart system and force Restart

>#### **rm (-rf)** - Remove files or directory !!ALL 

>#### **rmdir** - Removes Directories !!ONLY EMPTY FOLDERS!!

>#### **sudo** - (Super user do) - Gives the permits necessary to execute files or programs

>#### **touch** - Creates a new file 
>> `touch xxxx.xx` - _creates a new file_

>#### **whereis** - Will look for programs ONLY 

>#### **find** - Will let you find folders or files

>#### **which** - Tells you which version of a program is being used
>> `which node` - _will tell you which version of node is being used_

>#### **whoami** - Shows the pc user info

>#### **alias** - Allows to create shorter versions of commands

>#### **cntrl (strg) S** - Saves automatically ( you must press ctrl keep it holded and then the letter S )


>#### **apt update** - Updates all programs need for update in the pc

>#### **check chmod**

>#### **;** - will let you make 2 commands in one while the second one happening either the first succed or not
>> `mkdir -p a/b/c;touch filenameyouwant.xx` - **_thee will be 3 folders created one inside the other and in the last one (the C folder) will be the file: `filenameyouwant.xx`_**

>#### **&&** will let you make 2 commands in one line if the first succeed then the second one can happen

<br>

## **Information and Help**
>#### Both command show info about a command

> #### **--help** - This one shows the information on the same terminal

> #### **man** - This one shows the information inside program nano

<br>

## **Folder shortcuts**

>#### **.** - used to indicate a path. Tells Terminal you start in same directory
>> `touch xxx.xx ./previous folder` - Will create the file in the previus folder after stating that your starting point is the current folder.

>#### **..** used to go back one folder
>> `cd .. `

>#### **~**- takes you to the root folder
>> `cd ~`

>#### **-** - Goes between the folder you are NOW and the one before
>> `cd -`

>####  ° -

>#### / - Used to indicate paths
>> `cd xxx/xxxx/xxxx.xx`

## **Command for text files**

>#### **less** - Read only txt files

>#### **head** - Shows only first lines of txt document

>#### **tail** - Shows only last lines of txt document

>#### **nano** - text editor (newer version)

>#### **pico** - text editor (older version)  
---  
<br>

# Git Resources

[Intro to Git (Spanish)](https://www.youtube.com/playlist?list=PLU8oAlHdN5BlyaPFiNQcV0xDqy0eR35aU)
