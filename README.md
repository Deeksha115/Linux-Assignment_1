![](./z3vb4lwt.png){width="4.28125in" height="0.78125in"}

> **[1. Make a Directory:]{.underline}**
>
> **●** **Command** **Definition:**
>
> ○ mkdir: Used to create a directory ● **Command:**
>
> ○ mkdir Linux ● **Description:**
>
> ○ mkdir: It is used to create a directory ○ Linux: It is the name of
> the folder

**output**

ubuntu@test:\~\$ mkdir Linux ubuntu@test:\~\$ ls

**Linux**

> **[2. Remove a Directory:]{.underline}**
>
> ● **Command** **Definition:**
>
> ○ rmdir: Used to remove an empty directory ● **Command:**
>
> ○ rmdir Linux ● **Description:**
>
> ○ rmdir: It is used to remove an empty directory
>
> ○ Linux: It is the name of the folder to be removed

![](./u5vnms3o.png){width="4.427083333333333in"
height="0.5625in"}**output** ubuntu@test:\~\$ rmdir Linux
ubuntu@test:\~\$ ls

![](./td5ypxjf.png){width="4.645833333333333in" height="1.5in"}

> **[3. Make a Copy of a File:]{.underline}**
>
> ● **Command** **Definition:**
>
> ○ cp: Used to copy files or directories ● **Command:**
>
> ○ cp sourcefile Destinationfile ● **Description:**
>
> ○ cp: It is used to copy files or directories
>
> ○ sourcefile: current file which file you want to copy
>
> ○ Destinationfile: Destination file means where your files you want to
> copy

**Output**

ubuntu@test:\~\$ ls

filename1

ubuntu@test:\~\$ cp filename1 filename2

ubuntu@test:\~\$ ls

filename1 filename2

ubuntu@test:\~\$

> ● In this output i have a file which name is filename1 and i want to
> copy into filename2 so used the cp command the filename1 is copy into
> filname 2
>
> **[4. Move or Rename a File:]{.underline}**
>
> ● **Command** **Definition:**
>
> ○ mv: Used to move or rename files and directories ● **Command:**
>
> ○ mv file.txt new_location/
>
> ○ mv old_name.txt new_name.txt ● **Description:**
>
> ○ mv: It is used to move or rename files and directories ○ file.txt:
> Source file or directory
>
> ○ new_location/: Destination directory (for moving) ○ old_name.txt:
> Current name of the file
>
> ○ new_name.txt: New name for the file

**output**

ubuntu@test:\~\$ mv filename1 deeksha

ubuntu@test:\~\$ ls

deeksha filename2

ubuntu@test:\~\$ ls

deeksha filename2

ubuntu@test:\~\$ mkdir test

ubuntu@test:\~\$ ls

deeksha filename2 test

ubuntu@test:\~\$ pwd

/home/ubuntu

ubuntu@test:\~\$ mv deeksha /home/ubuntu/test/

ubuntu@test:\~\$ ls

filename2 test

ubuntu@test:\~\$ cd test/

ubuntu@test:\~/test\$ ls

![](./pzetpjpm.png){width="5.59375in"
height="3.9479166666666665in"}

deeksha

ubuntu@test:\~/test\$

> ● First i have a two files filename1 and filename2 Now i am renaming a
> filename1 to deeksha
>
> ● Command : mv filename1 deeksha
>
> ● Second i have a two file name which is deeksha and filename2 and one
> folder which is test
>
> ● Pwd shows the your current location
>
> ● Now i am going to move file the name of deeksha into test folder
> with the given command
>
> ● Command : mv deeksha /home/ubuntu/test/
>
> ● Now i am checking the file is in test folder or not with the command
> line ● cd test
>
> ● ls

![](./fvkhv5xv.png){width="5.65625in"
height="1.1145833333333333in"}

> **[5. Create an Empty File:]{.underline}**
>
> ● **Command** **Definition:**
>
> ○ touch: Used to create an empty file ● **Command:**
>
> ○ touch demo ● **Description:**
>
> ○ touch: It is used to create an empty file ○ demo: Name of the file
> to be created

**Output**

ubuntu@test:\~\$ touch demo

ubuntu@test:\~\$ ls

demo filename2 test

ubuntu@test:\~\$

> **[6. Remove Multiple Files with a Single]{.underline}**
> **[Command:]{.underline}**
>
> ● **Command** **Definition:**
>
> ○ rm: Used to remove files or directories ● **Command:**
>
> ○ rm file1.txt file2.txt ● **Description:**
>
> ○ rm: It is used to remove files or directories
>
> ○ file1.txt file2.txt: Names of the files to be removed

![](./ynud1izg.png){width="6.270833333333333in"
height="1.5104166666666667in"}

ubuntu@test:\~\$ ls

demo filename1 filename2 filename3 filename4 test

ubuntu@test:\~\$ rm filename1 filename2 filename3 filename4 demo

ubuntu@test:\~\$ ls

test

ubuntu@test:\~\$

> ● Here i have 5 files which is demo ,filename1, filename2 ,filename3,
> filename4 and i want to remove or delete it with the single command
> line and the command is given below
>
> ● rm demo filename1 filename2 filename3 filename4
>
> **[7. Remove Content from a Folder Without]{.underline}** **[Removing
> the Folder:]{.underline}**
>
> ● **Command** **Definition:**
>
> ○ rm -r folder/\* ● **Command:**
>
> ○ rm -rf folder/\* ● **Description:**
>
> ○ rm -rf: Recursive removal
>
> ○ folder/\*: All content inside the folder

![](./drvi3cju.png){width="6.270833333333333in"
height="3.3020833333333335in"}

> ● I have a folder which name is test and a filename demo inside the
> same directory which is demo
>
> ● rm -rf /home/ubuntu/test/demo
>
> **[8. Create Multiple Folders (a-z) with a Single]{.underline}**
> **[Command:]{.underline}**
>
> ● **Command** **Definition:** ○ mkdir {a..z}
>
> ● **Command:**
>
> ○ mkdir {a..z} ● **Description:**
>
> ○ mkdir: It is used to create a directory
>
> ○ {a..z}: Range of folder names from \'a\' to \'z\'

ubuntu@test:\~\$ mkdir {a..z} ubuntu@test:\~\$ ls

![](./g5jxh33y.png){width="6.270833333333333in"
height="0.71875in"}a b c d e f g h i j k l m n o p q r s t test u v w x
y z ubuntu@test:\~\$
