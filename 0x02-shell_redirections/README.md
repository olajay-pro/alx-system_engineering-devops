This folder consists of various Shell I/O redirection commands, all of which has been made excuteable. Below is a quick description of what each code does;

__NB: the numbering in this file co-responses to the numbering in each file__

0. This is a simple shell script that print out "Hell world"
1. The script displays a particular smiley
2. It displays the content of a file, which in the case is "/etc/passwd"
3. Display the content of two files at the same time, in this file of code the files been displayed are "/etc/passwd" and "/etc/hosts"
4. This displays the last lines of a stated file
5. This displays the first 10 lines a a stated file
6. Displays the third line only of a stated file, without using the sed command
7. A shell script that creates a file, which contains a certain text {the particular file created needed "\" to escape the use of special character which the name in this code contained}
8. A script that writes into a file {in this case "ls_cwd_content"}, the result of a command {ls -la}
9. This duplicates the last line of a file
10. This deletes all the regukar files with an stated extension {.js} that is present in the working directory and all its subfolders
11. This script count the number of directories and sub-directories in the current directory, in this script, the current and parent directories are not taken into account but the hidden directory are counted.
/NB: mindepth can be substitued for maxdepth, they both mean and do the same thing. -type d means directory and wc -l cou ts the lines of the input/
12. This script dispalys the 10 newest files in the current directory, sorted from the newest to the oldest
13. This shell code takes a list of words as input and only pritnt words that appear once
14. This displays lines that contain the pattern "root" from a stated file
15. This counts the number of lines that contains a pattern of "bin" in a stated files and then displays it
16. This would display lines containing a pattern, root, and three lines after them in a file that is stated
17. Displays all the lines of a stated file that doesnt contain a particular pattern
18. Displays all the lines of a file starting with a letter, both upper case and lower case
19. This replaces all character A and c from input to Z and e
20. This removes all letters c and C from input
21. This script will reverse its input
22. This code displays all users and their home directories, and it wolud be sorted by user

__NB: the numbering from here changes but still co-responds with the numbers on the files above__

100. The command finds all empty files and directories in the current and sub directories. Only the name of the files and directories is displayed not the entire path, hidden files are also listed 
101. This script lists all the files, not directory, with a .gif extension in the current and all its sub directories. the files are displayed with out their extention
102. This script decodes ACROSTICS {Acrostic is a form of writing in which the first letter/syllable/word of each line spells out a word or message} that use the first letter of each line
103. This scripts parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses, in the order of number of requests, most active host or IP at the top, which did the most requests