This is the readme file for 0x02-shell directions
1. echo "Hello, World"
2. "\"(Ôo)'" - Write a script that displays a confused smiley "(Ôo)'. The back slash is called escape character which prevents the next character from being interpreted as a special character
3. tail -n 10 /etc/passwd: Display the last 10 lines of /etc/passwd
4. head -n 10 /etc/passwd: Display the first 10 lines of /etc/passwd 
5. cat filename | head -3 | tail -1 : print the third lind of the file
6. ls -la > ls-cwd_content: Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
7. tail -1 iacta >> iacta : Duplicating the last line of a file in the same file
8. find .  -type f -name "*.js" -delete: Delete all .js files in the current working directory
9. find . -type d ! -path . | wc -l: Counts all parent directories, subdirectories and hidden directories
10. sort | uniq -u : Create a script that takes a list of words as input and prints only words that appear exactly once
11. egrep "root" /etc/passwd : - Display lines containing the pattern “root” from the file /etc/passwd
12. grep "bin" /etc/passwd | wc -l : grep looks for the matching files and wc counts it.
13. grep -A 3 "root" /etc/passwd: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
14. egrep -v "bin" /etc/passwd : Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
15. egrep ^[[:alpha:]] /etc/ssh/sshd_config - Display all lines of the file /etc/ssh/sshd_config starting with a letter
16. tr A Z | c e: Replace all characters A and c from input to Z and e respectively
17. tr -d C | tr -d c :- a script that removes all letters c and C from input
18. rev - Write a script that reverse its input
19. cut -d ':' -f 1.6 /etc/passwd | sort
