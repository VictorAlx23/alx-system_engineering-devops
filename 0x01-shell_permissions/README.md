README file for shell permission
1. su - Create a script that switches the current user to the user 
2. whoami - Write a script that prints the effective username of the current user
3. groups - Write a script that prints all the groups the current user is part of.
4. chown betty hello - Write a script that changes the owner of the file hello to the user betty
5. touch hello - Write a script that creates an empty file call
6. chmod u+x hello - a script that allows execution permit for the file hello
7. chmod ug+x,o+r - script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello u - owner g - group x -execution o - others r - read
8. chmod ugo+x hello - script that adds execution permission to the owner, the group owner and the other users, to the file hello
9. chmod 007 hello - others alone have full permission rwx to the file hello
10. chmod 753 hello - script that sets permission to -rwxr-x-wx
11. chmod --reference=olleh hello - Write a script that sets the mode of the file hello the same as olleh’s mode
12. chmod -R +X . - script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12. mkdir -m 751 my_dir - create a directory with specified permissions
