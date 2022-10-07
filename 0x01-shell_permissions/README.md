# 0x01. Shell, permissions
1. [0-iam_betty](0-iam_betty) - switches the current user to the user betty.
2. [1-who_am_i](1-who_am_i) - prints the effective username of the current user.
3. [2-groups](2-groups) - prints all the groups the current user is part of.
4. [3-new_owner](3-new_owner) - changes the owner of the file hello to the user betty.
5. [4-empty](4-empty) - creates an empty file called hello.
6. [5-execute](5-execute) - adds execute permission to the owner of the file hello.
7. [6-multiple_permissions](6-multiple_permissions) - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
8. [7-everybody](7-everybody) - adds execution permission to the owner, the group owner and the other users, to the file hello
9. [8-James_Bond](8-James_Bond) - sets the permission to the file hello as follows:
* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions
10. [9-John_Doe](9-John_Doe) - sets the mode of the file hello to this:
```
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```
11. [10-mirror_permissions](10-mirror_permissions) - sets the mode of the file hello the same as olleh’s mode.
12. [11-directories_permissions](11-directories_permissions) - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users without changing regular files
13. [12-directory_permissions](12-directory_permissions) - creates a directory called my_dir with permissions 751 in the working directory.
