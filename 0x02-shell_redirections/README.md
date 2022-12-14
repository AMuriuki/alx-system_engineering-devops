# 0x02. Shell, I/O Redirections and filters

## Learning Objectives
### Shell, I/O Redirection
* What do the commands head, tail, find, wc, sort, uniq, grep, tr do
* How to redirect standard output to a file
* How to get standard input from a file instead of the keyboard
* How to send the output from one program to the input of another program
* How to combine commands and filters with redirections

### Special Characters
* What are special characters
* Understand what white spaces, single quotes, double quotes, backslash, comment, pipe, command separator, tilde do and how and when to use them

### Other Man Pages
* How to display a line of text
* How to concatenate files and print on the standard output
* How to reverse a string
* How to remove sections from each line of files
* What is the /etc/passwd file and what is its format
* What is the /etc/shadow file and what is its format

| Filename | Description | 
| ------------ | -------------- |
| [0-hello_world](0-hello_world) | prints `“Hello, World”`, followed by a new line to the standard output. |
| [2-hellofile](2-hellofile) | displays the content of the `/etc/passwd` file. |
| [3-twofiles](3-twofiles) | displays the content of `/etc/passwd` and /etc/hosts |
| [4-lastlines](4-lastlines) | displays the last 10 lines of `/etc/passwd` |
| [5-firstlines](5-firstlines) | displays the first 10 lines of `/etc/passwd` |
| [6-third_line](6-third_line) | displays the third line of the file `iacta`. |
| [7-file](7-file) | creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text Best School ending by a new line. |
| [8-cwd_state](8-cwd_state) | writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it will be overwritten. If the file `ls_cwd_content` does not exist, it will create it. |
| [9-duplicate_last_line](9-duplicate_last_line) | duplicates the last line of the file `iacta` |
| [10-no_more_js]() | deletes all the regular files with a `.js` extension that are present in the current directory and all its subfolders. |
| [11-directories]() | counts the number of directories and sub-directories in the current directory. |
| [12-newest_files]() | displays the 10 newest files in the current directory. |
| [13-unique](13-unique) | takes a list of words as input and prints words that appear exactly once in a sorted manner. |
| [14-findthatword](14-findthatword) | displays lines containing the pattern `“root”` from the file `/etc/passwd` |
| [15-countthatword](15-countthatword) | displays the number of lines that contain the pattern `“bin”` in the file `/etc/passwd` |
| [16-whatsnext](16-whatsnext) | display lines containing the pattern `“root”` and 3 lines after them in the file `/etc/passwd`. |
| [17-hidethisword](17-hidethisword) | Display all the lines in the file `/etc/passwd` that do not contain the pattern `“bin”`. |
| [18-letteronly](18-letteronly) | displays all lines of the file `/etc/ssh/sshd_config` starting with a letter. |
| [19-AZ](19-AZ) | replace all characters `A` and `c` from input to `Z` and `e` respectively. |
| [20-hiago](20-hiago) | removes all letters `c` and `C` from input. | 
| [21-reverse]() | reverse its input. |
| [22-users_and_homes](22-users_and_homes) | displays all users and their home directories, sorted by users based on the the `/etc/passwd` file |
| [100-empty_casks](100-empty_casks) | finds all empty files and directories in the current directory and all sub-directories. |
| [101-gifs](101-gifs) | lists all the files with a `.gif` extension in the current directory and all its sub-directories.<br> sorted by byte values, but case-insensitive (file `aaa` is listed before file `bbb`, file `.b` is listed before file `a`, and file `Rona` is listed after file `jay`) | 
| [102-acrostic](102-acrostic) | decodes acrostics that use the first letter of each line.






