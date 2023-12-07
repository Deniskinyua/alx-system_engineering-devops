### 0x01. SHELL PERMISSIONS

> General Requirements
- Allowed editors: vi, vim, emacs
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long ($ wc -l file should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly #!/bin/bash
- A README.md file, at the root of the folder of the project, describing what each script is doing
- You are not allowed to use backticks, &&, || or ;
- All your files must be executable
#### Tasks
 0. Task 0: My Name is Betty
> Create a script that switches the current user to the user betty.

- You should use exactly 8 characters for your command (+1 character for the new line)
- You can assume that the user betty will exist when we will run your script
>> 0-iam_betty

1. Task 1: Who AM I
> Write a script that prints the effective username of the current user.
>> 1-who_am_i

2. Task 2: Groups
> Write a script that prints all the groups the current user is part of.
>> 2-groups

3. Task 3: New Owner
> Write a script that changes the owner of the file hello to the user betty.
>> 3-new_owner

4. Task 4: Empty!
> Write a script that creates an empty file called hello.
>> 4-empty

5. Task 5: Execute
> Write a script that adds execute permission to the owner of the file hello (6-multiple_permissions)
>> 5-execute

6. Task 6: Multiple Permisions
> Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello (The file hello will be in the working directory)
>> 6-multiple_permissions

7. Task 7: Everybody
> Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello.
- The file hello will be in the working directory
- You are not allowed to use commas for this script
>> 7-everybody

8. Task 8: James Bond
> Write a script that sets the permission to the file hello as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions
- The file hello will be in the working directory You are not allowed to use commas for this script
>> 8-James_Bond
