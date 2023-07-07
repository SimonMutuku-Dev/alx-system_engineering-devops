0X01-SHELL_PERMISSIONS

Basic
0-iam_betty => Switch users
1-who_am_i => Prints the current user logged in
2-groups => Prints all the groups the current user is part of
3-new_owner => Changes the owner of file
4-empty => Create empty file
5-execute => Sets permission to execute file:owner
6-multiple_permissions => Sets permission to execute file:owner/group and permission to read file:others

7-everybody => Sets permission to execute file:owner/group/others
8-James_Bond => Sets permission to read, write and execute a file:others while no permissions for file:owner/group

9-John_Doe => Sets full permissions file:owner, permission to read and execute file:group and permission to write and execute file:others

10-mirror_permissions => Copy file permissions
11-directories_permissions => Set permission to execute subdirectories:owner/group/others
12-directory_permissions => Create directory & set permissions
13-change_group => Change permission file:group

Advanced
100-change_owner_and_group => Change permissions recursively:owner/group
101-symbolic_link_permissions => Change permission of symlink file:owner/group respectively
102-if_only => Change permission of file:owner only if owned by a specific user
103-Star_Wars => Play the StarWars IV episode in the terminal.
