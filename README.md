**1. Make a Directory:**

- **Command Definition:**

  - `mkdir`: Used to create a directory

- **Command:**

  - `mkdir Linux`

- **Description:**

  - `mkdir`: It is used to create a directory

  - `Linux`: It is the name of the folder

**output**

ubuntu\@test:\~$ mkdir Linux

ubuntu\@test:\~$ ls

**Linux**

![](https://lh7-us.googleusercontent.com/XsLMWlCcX1CuSoIdm8hfjh8pp05BKJcWYnlnvUTHkq78jxWJ6Zxfn1Qr16x3Hi-3gKGJBusZggFD15miDejZs7VNYNQOJkOQlWtNloV2zpfFwyUF0PzMRdo41xp9PRP48eX2okt4TS-m4GLdCqovBqI)

\


**2. Remove a Directory:**

- **Command Definition:**

  - `rmdir`: Used to remove an empty directory

- **Command:**

  - `rmdir Linux`

- **Description:**

  - `rmdir`: It is used to remove an empty directory

  - `Linux`:  It is the name of the folder to be removed

**output**

ubuntu\@test:\~$ rmdir Linux

ubuntu\@test:\~$ ls

****![](https://lh7-us.googleusercontent.com/Zde4lgpjp9lBYQF2F6HZPLqG-KeMrdzzwqYlsFO_PRKmVQ2-sgwmY5sSXkRP8LPHYZVvGhwm-ANk4uXUMgrTFL4DXm9uDlEsr8E-7c7mvOoyMrtlC0pwi0dpQ4MKb4hOWCiJOqB1iBwKFtehAdZZ9hw)****

\
\
\
\
\
\


**3. Make a Copy of a File:**

- **Command Definition:**

  - `cp`: Used to copy files or directories

- **Command:**

  - `cp sourcefile Destinationfile`

- **Description:**

  - `cp`: It is used to copy files or directories

  - `sourcefile`: current file which file you want to copy

  - `Destinationfile`: Destination file means where your files you want to copy 

**Output**

ubuntu\@test:\~$ ls

filename1

ubuntu\@test:\~$ cp filename1 filename2

ubuntu\@test:\~$ ls

filename1  filename2

ubuntu\@test:\~$

****![](https://lh7-us.googleusercontent.com/Ii5d5wmqur2mu-l3OqZl0kIu0ahisHoEkRLSbXjJicgcl0tcYjy8ODtWM3V1_L_sRWVvEUPOkz0aijlaePw5IB8fMhCRunT6Zr6C6W3OaNkQRax1XdsL7Nmzvn5dl6W3H2DsXpN3qK6sf-Up6fao-H0)****

- In this output i have a file which name is filename1 and i want to copy into filename2 so used the cp command the filename1 is copy into filname 2 

\
\
\
\
\


**4. Move or Rename a File:**

- **Command Definition:**

  - `mv`: Used to move or rename files and directories

- **Command:**

  - `mv file.txt new_location/`

  - `mv old_name.txt new_name.txt`

- **Description:**

  - `mv`: It is used to move or rename files and directories

  - `file.txt`: Source file or directory

  - `new_location/`: Destination directory (for moving)

  - `old_name.txt`: Current name of the file

  - `new_name.txt`: New name for the file

**output** 

ubuntu\@test:\~$ mv filename1 deeksha

ubuntu\@test:\~$ ls

deeksha  filename2

ubuntu\@test:\~$ ls

deeksha  filename2

ubuntu\@test:\~$ mkdir test

ubuntu\@test:\~$ ls

deeksha  filename2  test

ubuntu\@test:\~$ pwd

/home/ubuntu

ubuntu\@test:\~$ mv deeksha /home/ubuntu/test/

ubuntu\@test:\~$ ls

filename2  test

ubuntu\@test:\~$ cd test/

ubuntu\@test:\~/test$ ls

deeksha

ubuntu\@test:\~/test$

![](https://lh7-us.googleusercontent.com/EFzFL_9oiraNRKp03IP9EDxpUYni3ylt6TfJR3D-8dYEw35-n9tFcrgBNVc8cA8T8PH-m8dUPXpjHrQAsFp4BcIjTs4QCO-ck91sZ1viYgzutL2YYmBT687zWdOE2ZJgzVMmCSTLFjAnKWCVI8ho-hQ)

- First i have a two files filename1  and filename2 Now i am renaming a filename1 to deeksha 

- Command : mv filename1 deeksha 

- Second i have a two file name which is deeksha and filename2 and one folder which is test 

- Pwd shows the your current location 

- Now i am going to move file the name of deeksha into test folder with the given command

- Command : mv deeksha /home/ubuntu/test/

- Now i am checking the file is in test folder or not with the command line 

- cd test

- ls 

\
\
\
\


**5. Create an Empty File:**

- **Command Definition:**

  - `touch`: Used to create an empty file

- **Command:**

  - `touch demo`

- **Description:**

  - `touch`: It is used to create an empty file

  - `demo`: Name of the file to be created

**Output**

ubuntu\@test:\~$ touch demo

ubuntu\@test:\~$ ls

demo  filename2  test

ubuntu\@test:\~$

![](https://lh7-us.googleusercontent.com/ZinIyTHXtjc0y0p6xjR92QYWCdRoIWTrVRFSL0zUrXv9RLtXZUFXUOKXfveocQMMvj6b0Zf5VKsrfKW3CEZe4xLVHmClCa4O8_WoJpM23teRHbtIPtUbEXWS32mpRmdr-7uCD15GgoR7rX10Tmss4kM)

**6. Remove Multiple Files with a Single Command:**

- **Command Definition:**

  - `rm`: Used to remove files or directories

- **Command:**

  - `rm file1.txt file2.txt`

- **Description:**

  - `rm`: It is used to remove files or directories

  - `file1.txt file2.txt`: Names of the files to be removed

\
\
\


ubuntu\@test:\~$ ls

demo  filename1  filename2  filename3  filename4  test

ubuntu\@test:\~$ rm filename1 filename2 filename3 filename4 demo

ubuntu\@test:\~$ ls

test

ubuntu\@test:\~$

![](https://lh7-us.googleusercontent.com/ZhauYlZ48K1ZVE2zvm88Wpu1qONKNQY65iQxdSsLKpVcO4uGXAEp111fRdEqD5iZd5ILmdDKlkZ4ZSWQh9vwv4eWaRv58Sx6ZrXqpjHHfJmnhPCrJpPKes47VOCbbZf89q2qadOSFpvJDA5rcSAG6vc)

- Here i have 5 files which is demo ,filename1, filename2 ,filename3, filename4 and i want to remove or delete it with the single command line and the command is given below 

- rm demo filename1 filename2 filename3  filename4 

\
\


**7. Remove Content from a Folder Without Removing the Folder:**

- **Command Definition:**

  - `rm -r folder/*`

- **Command:**

  - `rm -rf folder/*`

- **Description:**

  - `rm -rf`: Recursive removal

  - `folder/*`: All content inside the folder

![](https://lh7-us.googleusercontent.com/Zo47BSJX9AmbhKW2-Bxu6qqjjL6YJF2rZMaSKi4j6Bf_y5nrKFOQj3Qp0fWOFIiL1YBTuGWJaRb9y1vhqu5ds1BEB5mKdlEvM9cVKE8WJCHnPk4fPK4oBkHbdTbxAla0_bcMFrVm1YXpSMQ7fDddmI0)

- I have a folder which name is test and a filename demo inside the same directory which is demo 

- rm -rf /home/ubuntu/test/demo

\
\
\


**8. Create Multiple Folders (a-z) with a Single Command:**

- **Command Definition:**

  - `mkdir {a..z}`

- **Command:**

  - `mkdir {a..z}`

- **Description:**

  - `mkdir`: It is used to create a directory

  - `{a..z}`: Range of folder names from 'a' to 'z'

\
\
\
\


ubuntu\@test:\~$ mkdir {a..z}

ubuntu\@test:\~$ ls

a  b  c  d  e  f  g  h  i  j  k  l  m  n  o  p  q  r  s  t  test  u  v  w  x  y  z

ubuntu\@test:\~$

\
\


![](https://lh7-us.googleusercontent.com/MFuur1QXPYN2MTHOyx-aedWDle46wK8o4XUpXMNQU_p9yOrNcHcEdbJDyXnx0lZYI850gAzCAjH8w-Es3w3XFt-Rv2Ygvnr2jnu0pRYWGU8-KzsRWgqLhUyodDtXuGOISkDvW4Wfk-FQNh1ZYCxSUyw)
