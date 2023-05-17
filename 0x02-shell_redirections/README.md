# 0x02-shell_redirections
This project is all about Standard Input and Output O/I redirection. It is my probation month project at ALX <br>
Created Monday 15th May, 2023

Useful Resources:<br>
[Special Character](http://mywiki.wooledge.org/BashGuide/SpecialCharacters)<br>
[Linux I/O Redirection](http://linuxcommand.org/lc3_lts0070.php)<br>
[Youtube Guide](https://www.youtube.com/watch?v=B7nHENGa7pc)<br>
[Before/After Match in Shell](https://linuxhint.com/show-lines-before-after-match-via-grep/)<br>
[Search A File for Pattern](https://www.ibm.com/docs/en/i/7.1?topic=data-grep)<br>
[Finding Text String](https://www.ibm.com/docs/en/aix/7.2?topic=files-finding-text-strings-within-grep-command)
<br><br>
To run two letter file name as one in shell command e.g file name = file\ name (The \ terminates the whitespace and run it as a single command)
### Pipeline or Pipe <br>Is the ability to combine two commands together as one e.g. cut -c1 | tr -d "[:blank:]" (This combines commands cut -c1 - meaning cut first character and tr -d "[:blank:]" - delete all white space)

### Question
1. Write a script that prints “Hello, World”, followed by a new line to the standard output.
2. Display the content of the /etc/passwd file.
3. Display the content of /etc/passwd and /etc/hosts
4. Display the last 10 lines of /etc/passwd
5. Display the first 10 lines of /etc/passwd
6. Write a script that displays the third line of the file iacta. The file iacta will be in the working directory. You’re not allowed to use sed
7. Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8. Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9. Write a script that duplicates the last line of the file iacta. The file iacta will be in the working directory
10. Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. Write a script that counts the number of directories and sub-directories in the current directory. The current and parent directories should not be taken into account. Hidden directories should be counted
12. Create a script that displays the 10 newest files in the current directory.<br>
Requirements:<br>
One file per line<br>
Sorted from the newest to the oldest
13.  Create a script that takes a list of words as input and prints only words that appear exactly once.<br>
Input format: One line, one word<br>
Output format: One line, one word<br>
Words should be sorted
14.  Display lines containing the pattern “root” from the file /etc/passwd
15.  Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16.  Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17.  Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18.  Display all lines of the file /etc/ssh/sshd_config starting with a letter. include capital letters as well
19.  Replace all characters A and c from input to Z and e respectively.
20.  Create a script that removes all letters c and C from input.
21.  Write a script that reverse its input.
22.  Write a script that displays all users and their home directories, sorted by users. Based on the the /etc/passwd file
23.  Write a command that finds all empty files and directories in the current directory and all sub-directories.<br>
Only the names of the files and directories should be displayed (not the entire path)<br>
Hidden files should be listed<br>
One file name per line<br>
The listing should end with a new line<br>
You are not allowed to use basename, grep, egrep, fgrep or rgrep
24.  Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.<br>
Hidden files should be listed<br>
Only regular files (not directories) should be listed<br>
The names of the files should be displayed without their extensions<br>
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)<br>
One file name per line<br>
The listing should end with a new line<br>
You are not allowed to use basename, grep, egrep, fgrep or rgrep
25.  An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more.<br>
Create a script that decodes acrostics that use the first letter of each line.<br>
The ‘decoded’ message has to end with a new line<br>
You are not allowed to use grep, egrep, fgrep or rgrep
26.  Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.<br>
Order by number of requests, most active host or IP at the top<br>
You are not allowed to use grep, egrep, fgrep or rgrep
