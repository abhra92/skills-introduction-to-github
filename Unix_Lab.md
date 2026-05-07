# Unix Commands with Uses, Syntax, Example and Output

---

## Page 01 — Basic File & Directory Commands

### 1. pwd (Print Working Directory)
- **Use:** Shows the full path of the current directory.
- **Syntax:** `pwd`
- **Example:** `$ pwd`
- **Output:** `/home/Ubuntu`

---

### 2. ls (List Files)
- **Use:** Displays files and folders in the current directory.
- **Syntax:** `ls`
- **Example:** `$ ls`
- **Output:**
  ```
  Desktop  Documents  Downloads  Music  Pictures
  file1.txt  file2.txt  tridib.txt  tz.sh
  ```

---

### 3. ls -l (Long List)
- **Use:** Shows detailed information about files and folders.
- **Syntax:** `ls -l`
- **Example:** `$ ls -l`
- **Output:**
  ```
  total 0
  drwxr-xr-x 2 ubuntu ubuntu  60 Apr 10 12:22 Desktop
  drwxr-xr-x 2 ubuntu ubuntu  40 Apr 10 17:48 Documents
  drwxr-xr-x 2 ubuntu ubuntu  40 Apr 10 17:48 Downloads
  drwxr-xr-x 2 ubuntu ubuntu  40 Apr 10 17:48 Music
  drw-wxr-xr-x 2 ubuntu ubuntu  40 Apr 10 17:48 Pictures
  -rw-rw-r-- 1 ubuntu ubuntu   0 Apr 10 19:37 file1.txt
  -rw-rw-r-- 1 ubuntu ubuntu   0 Apr 10 19:37 file2.txt
  drw-------  6 ubuntu ubuntu 120 Apr 10 18:02 snap
  -rw-rw-r-- 1 ubuntu ubuntu   0 Apr 10 19:37 trash
  -rw-rw-r-- 1 ubuntu ubuntu   0 Apr 10 19:37 tridib.sh
  ```

---

## Page 02 — Directory Management Commands

### 4. ls -a (Show Hidden Files)
- **Use:** Display all files, including hidden files.
- **Syntax:** `ls -a`
- **Example:** `$ ls -a`
- **Output:**
  ```
  .               .bashrc       .grfs         .sudo-as-admin-successful
  ..              .cache        .local        Desktop    Music
  .bash_history   .config       .profile      Documents  Pictures
  .bash_logout    .gnupg        .ssh          Downloads  file1.txt
  ```

---

### 5. cd (Change Directory)
- **Use:** Changes from one directory to another.
- **Syntax:** `cd foldername`
- **Example:** `$ cd Documents`
- **Output:** (Directory changed)

---

### 6. mkdir (Make Directory)
- **Use:** Creates a new folder.
- **Syntax:** `mkdir directoryname`
- **Example:** `$ mkdir project`
- **Output:** (folder created)

---

### 7. rmdir (Remove Empty Directory)
- **Use:** Deletes an empty folder.
- **Syntax:** `rmdir directoryname`
- **Example:** `$ rmdir test`
- **Output:** (folder removed)

---

## Page 03 — File Operations

### 8. touch (Create File)
- **Use:** Creates a new empty file.
- **Syntax:** `touch filename`
- **Example:** `$ touch notes.txt`
- **Output:** (file created)

---

### 9. cat (Display File Content)
- **Use:** Shows the content of a file.
- **Syntax:** `cat filename`
- **Example:** `$ cat notes.txt`
- **Output:** `Hello World`

---

### 10. cp (Copy File)
- **Use:** Copies files or folder.
- **Syntax:** `cp source destination`
- **Example:** `$ cp file1.txt file2.txt`
- **Output:** (file copied)

---

### 11. mv (Move/Rename File)
- **Use:** Moves or renames files/folders.
- **Syntax:** `mv oldname newname`
- **Example:** `$ mv file1.txt file3.txt`
- **Output:** (file renamed)

---

### 12. rm (Remove File)
- **Use:** Deletes files.
- **Syntax:** `rm filename`
- **Example:** `$ rm notes.txt`
- **Output:** (file deleted)

---

## Page 04 — More Commands

### 13. rm -r (Remove Folder)
- **Use:** Deletes folders and their contents.
- **Syntax:** `rm -r directoryname`
- **Example:** `$ rm -r project`
- **Output:** (folder deleted)

---

### 14. clear (Clear Screen)
- **Syntax:** `clear`
- **Example:** `$ clear`
- **Output:** (Screen cleared)

---

### 15. date (Show Date)
- **Use:** Display and manipulate the system's date and time.
- **Syntax:** `date`
- **Example:** `$ date`
- **Output:** `Fri Apr 10 10:30:00 IST 2026`

---

### 16. cal (Calendar)
- **Use:** Display formatted calendars in the terminal.
- **Syntax:** `cal`
- **Example:** `$ cal`
- **Output:** Monthly Calendar

---

### 17. head (First Lines)
- **Use:** Displays the first few lines of a file.
- **Syntax:** `head filename`
- **Example:** `$ head notes.txt`
- **Output:** First 10 lines.

---

## Page 05 — File Content & Permissions

### 18. tail (Last Lines)
- **Use:** Displays the last few lines of a file.
- **Syntax:** `tail filename`
- **Example:** `$ tail notes.txt`
- **Output:** Last 10 lines

---

### 19. wc (Word Count)
- **Use:** Count number of newlines, words, characters and bytes.
- **Syntax:** `wc filename`
- **Example:** `$ wc notes.txt`
- **Output:** `10 50 300 notes.txt`

---

### 20. sort (Sort Content)
- **Use:** Arrange lines of a text file.
- **Syntax:** `sort filename`
- **Example:** `$ sort notes.txt`
- **Output:** (Sorted lines)

---

### 21. chmod (Change Permission)
- **Use:** Changes the permissions of a file or directory.
- **Syntax:** `chmod permission file`
- **Example:** `chmod 777 test.sh`
- **Output:** (Permission changed)

---

### 22. chown (Change Owner)
- **Use:** Change the user and group ownership of files.
- **Syntax:** `chown owner filename`
- **Example:** `$ chown user1 file.txt`
- **Output:** (ownership changed, no message shown)

---

## Page 06 — Advanced Commands

### 23. ln (Create Link)
- **Use:** Create a link to a file.
- **Syntax:** `ln source-file link-name`
- **Example:** `$ ln file.txt link1.txt`
- **Output:** (link created, no message shown)

---

### 24. echo (Display Text)
- **Use:** Displays text or variables on the terminal.
- **Syntax:** `echo text`
- **Example:** `$ echo Hello World`
- **Output:** `Hello World`

---

### 25. less (View File Page by Page)
- **Use:** Views file content page by page.
- **Syntax:** `less filename`
- **Example:** `$ less notes.txt`
- **Output:** (File Content Shown)

---

### 26. more (View File)
- **Use:** Displays file content screen by screen.
- **Syntax:** `more filename`
- **Example:** `$ more notes.txt`
- **Output:** (File Content Shown)

---

### 27. cmp (Compare Files)
- **Use:** Compare two files.
- **Syntax:** `cmp file1 file2`
- **Example:** `$ cmp a.txt b.txt`
- **Output:** (difference shown)

---

## Page 07 — Process & File Difference Commands

### 28. diff (Show File Difference)
- **Use:** Shows and compares files line by line.
- **Syntax:** `diff file1 file2`
- **Example:** `$ diff a.txt b.txt`
- **Output:** (Changed lines shown)

---

### 29. patch (Apply Differences to Files)
- **Use:** Applies a diff file to update a target file.
- **Syntax:** `patch original-file patch-file`
- **Example:** `$ patch file1.txt changes.diff`
- **Output:** `patching file file1.txt`

---

### 30. ps (Process Status)
- **Use:** Displays information about active processes, including their status and PIDs.
- **Syntax:** `ps`
- **Example:** `$ ps`
- **Output:** (Running Processes)

---

### 31. top (System Processes)
- **Use:** Displays dynamic real time view of system processes and their resource usage.
- **Syntax:** `top`
- **Example:** `$ top`
- **Output:** (Live process list)

---

### 32. kill (Stop Process)
- **Use:** Terminates processes using their process IDs (PIDs).
- **Syntax:** `kill PID`
- **Example:** `$ kill 1234`
- **Output:** (Process terminated)

---

## Page 08 — Disk, Search & Network Commands

### 33. df (Disk Space)
- **Use:** Report the amount of disk space used.
- **Syntax:** `df -h`
- **Example:** `$ df -h`
- **Output:** Disk usage details

---

### 34. du (Directory Size)
- **Use:** Estimate and display the amount of disk space.
- **Syntax:** `du -sh folder`
- **Example:** `$ du -sh project`
- **Output:** `20M project`

---

### 35. history (Command History)
- **Syntax:** `history`
- **Example:** `$ history`
- **Output:** Previous commands list

---

### 36. grep (Search Text)
- **Use:** Search for patterns in text files.
- **Syntax:** `grep word filename`
- **Example:** `$ grep hello notes.txt`
- **Output:** Matching line

---

### 37. find (Find File)
- **Use:** Search for files and directories based on various attributes.
- **Syntax:** `find . -name filename`
- **Example:** `$ find . -name notes.txt`
- **Output:** `./notes.txt`

---

## Page 09 — Network, Archive & System Commands

### 38. ping (Check Network)
- **Use:** Tests connectivity with another host using ICMP echo requests.
- **Syntax:** `ping host`
- **Example:** `$ ping google.com`
- **Output:** Reply from server

---

### 39. tar (Archive File)
- **Use:** Bundle multiple files and directories into a single archive file.
- **Syntax:** `tar -cvf file.tar folder`
- **Example:** `$ tar -cvf backup.tar docs`
- **Output:** Archive created

---

### 40. unzip (Extract Zip)
- **Use:** List, test and extracts files from zip archives.
- **Syntax:** `unzip file.zip`
- **Example:** `$ unzip test.zip`
- **Output:** Files extracted

---

### 41. passwd (Change Password)
- **Syntax:** `passwd`
- **Example:** `$ passwd`
- **Output:** Password updated

---

### 42. shutdown (Turn off System)
- **Syntax:** `shutdown now`
- **Example:** `$ shutdown now`
- **Output:** System shutting down

---

## Page 10 — Shell Scripts (Programs 1 & 2)

### Program 1: Display File Properties

**Task:** Write a UNIX shell script that takes a file name as user input and displays the file properties such as size, last modified date and permissions.

```bash
#!/bin/bash
echo "Enter file name:"
read filename
if [ -f "$filename" ]
then
    echo "File Properties:"
    ls -lh "$filename"
else
    echo "File does not exist."
fi
```

**Output:**
```
Enter file name:
test.txt
File Properties:
-rw-r--r-- 1 user user 20K Apr 14 10:30 test.txt
```

---

### Program 2: Check if File Exists

**Task:** Write a shell script that checks if a file exists. If it exists, print "File exists"; otherwise, print "File does not exist."

```bash
#!/bin/bash
echo "Enter file name:"
read filename
if [ -f "$filename" ]
then
    echo "File exists."
else
    echo "File does not exist."
fi
```

**Output:**
```
Enter file name:
filesh
File exists.
```

---

## Page 11 — Shell Scripts (Programs 3 & 4)

### Program 3: Create Directory, Change to It, Create File and Write Into It

**Task:** Write a shell script to perform the following tasks:
- Create a new directory
- Change to that directory
- Create a test file inside it
- Write "Hello UNIX" into the file

```bash
#!/bin/bash
mkdir mydirectory
cd mydirectory
echo "Hello UNIX" > file.txt
echo "Task completed successfully."
```

**Output:**
```
Task completed successfully.
```

---

### Program 4: Create File, Write Content and Display It

**Task:** Write a shell script that creates a new file, writes some content into the file and displays the content of the file.

```bash
#!/bin/bash
echo "Enter file name:"
read filename
echo "This is a sample text file." > $filename
echo "Content of the file:"
cat $filename
```

**Output:**
```
Enter file name:
myfile.txt
Content of the file:
This is a sample text file.
```

---

## Page 12 — Shell Scripts (Programs 5 & 6)

### Program 5: Check if File Exists in Current Directory

**Task:** Write a shell script that checks whether a file exists in the current directory. If it exists, print "File found"; otherwise, print "File not found".

```bash
#!/bin/bash
echo "Enter file name:"
read filename
if [ -f "$filename" ]
then
    echo "File found"
else
    echo "File not found"
fi
```

**Output:**
```
Enter file name:
tb.sh
File found
```

---

### Program 6: Read File Line by Line and Print to Console

**Task:** Write a shell script that opens a file for reading, reads the content line by line and prints it to the console.

```bash
#!/bin/bash
echo "Enter file name:"
read filename
while read line
do
    echo "$line"
done < $filename
```

**Output:**
```
Enter file name:
file.txt
Hello Unix.
```

---

## Page 13 — Shell Scripts (Programs 7 & 8)

### Program 7: Count Lines, Words and Characters in a File

**Task:** Write a shell script that reads the content of a file and counts the number of lines, words and characters in the file.

```bash
#!/bin/bash
echo "Enter file name:"
read filename
if [ -f "$filename" ]
then
    echo "File statistics:"
    wc $filename
else
    echo "File does not exist."
fi
```

**Output:**
```
Enter file name:
example.txt
File statistics:
2 5 27 example.txt
```

---

### Program 8: Copy Content of One File to Another

**Task:** Write a shell script that copies the content of one file to another file. The script should prompt the user for the source and destination file names.

```bash
#!/bin/bash
echo "Enter source file name:"
read source
echo "Enter destination file name:"
read destination
if [ -f "$source" ]
then
    cp $source $destination
    echo "File copied successfully."
```

---

## Page 14 — Program 8 (continued) & Program 9

*(Continuation of Program 8)*

```bash
else
    echo "Source file does not exist."
fi
```

**Output:**
```
Enter source file name:
example.txt
Enter destination file name:
newfile.txt
File copied successfully.
```

---

### Program 9: File Permissions using chmod and chown

**Task:**

**a) Create a file named mainfile.txt**
```bash
$ touch mainfile.txt
```

**b) Use the chmod to give the owner read, write and execute permissions**
```bash
$ chmod 700 mainfile.txt
```

**c) Use the ls -l chmod to view permissions and explain each part of the output**
```bash
$ ls -l mainfile.txt
```

*Example output:*
```
-rwx------ 1 user user 0 Apr 20 10:30 mainfile.txt
```

**d) Change the owner of the file using the chown command**
```bash
$ sudo chown newowner mainfile.txt
```

---

*End of Unix Lab Notes — 14 Pages*
