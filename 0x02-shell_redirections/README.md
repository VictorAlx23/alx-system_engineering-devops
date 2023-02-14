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
