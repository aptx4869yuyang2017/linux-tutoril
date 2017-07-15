# Permissions
* permission
    * r read 
    * w write 
    * x execute 
* 3 sets of people
    * owner
    * group 
    * others 
* View Permissions  `ls -l `
* Change Permission `chmod [permissions] [path]`  
    * [ugoa] - user (or owner), group, others, all
    *  granting or revoking the permission - indicated with either a plus ( + ) or minus ( - )
    * read ( r ), write ( w ) or execute ( x )
* Setting Permissions Shorthand
 

```table
Octal	| Binary
0 | 0 0 0
1| 0 0 1
2| 0 1 0
3| 0 1 1
4| 1 0 0
5| 1 0 1
6| 1 1 0
7| 1 1 1
```
* Permissions for Directories
    * r - you have the ability to read the contents of the directory (ie do an ls)
    * w - you have the ability to write into the directory (ie create files and directories)
    * x - you have the ability to enter that directory (ie cd)
