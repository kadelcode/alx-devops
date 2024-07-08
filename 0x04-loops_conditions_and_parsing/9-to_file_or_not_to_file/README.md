Write a Bash script that gives you information about the ```school``` file.
Requirements:

- You must use ```if``` and, ```else``` (case is forbidden)
- Your Bash script should check if the file exists and print:
  - if the file exists: ```school file exists```
  - if the file does not exist: ```school file does not exist```
- If the file exists, print:
  - if the file is empty: ```school file is empty```
  - if the file is not empty: ```school file is not empty```
  - if the file is a regular file: ```school is a regular file```
  - if the file is not a regular file: (nothing)
```
sylvain@ubuntu$ file school
school: cannot open `school' (No such file or directory)
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file does not exist
sylvain@ubuntu$ touch school
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is empty
school is a regular file
sylvain@ubuntu$ echo 'betty' > school 
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is not empty
school is a regular file
sylvain@ubuntu$ rm school 
sylvain@ubuntu$ mkdir school
sylvain@ubuntu$ ./9-to_file_or_not_to_file 
school file exists
school file is not empty
sylvain@ubuntu$ 
