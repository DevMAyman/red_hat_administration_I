### 1. Create a user account with the following attribute

<img src="./pics/01.png"/>


### 2. Create a user account with the following attribute

<img src="./pics/02.png"/>

### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000

<img src="./pics/03.png"/>


### 4. Create a supplementary group called badgroup

<img src="./pics/03.png"/>


### 5. Add islam user to the pgroup group as a supplementary group

<img src="./pics/05.png"/>


### 6. Modify the password of islam's account to password

<img src="./pics/06.png"/>


### 7. Modify islam's account so the password expires after 30 days

<img src="./pics/07.png"/>


### 8. Lock bad user account so he can't log in

<img src="./pics/08.png"/>


### 9. Delete bad user account

<img src="./pics/09.png"/>


### 10. Delete the supplementary group called badgroup.

<img src="./pics/10.png"/>


### 13. Create a folder called myteam in your home directory and change its permissions to <br/> read only for the owner.

<img src="./pics/13.png"/>


### 14. Log out and log in by another user

<img src="./pics/14.png"/>


### 15. Try to access (by cd command) the folder (myteam)

<img src="./pics/15.png"/>


### 16. Using the command Line
####    - Change the permissions of oldpasswd file to give owner read and write<br/>permissions and for group write and execute and execute only for the others<br/>(using chmod in 2 different ways)

<img src="./pics/16.png"/>


####    - Change your default permissions to be as above.

<img src="./pics/16-2.png"/>


####    - What is the maximum permission a file can have, by default when it is just <br>created? And what is that for directory.

<img src="./pics/16-3.png"/>


####    - Change your default permissions to be no permission to everyone then create a <br/> directory and a file to verify.

<img src="./pics/16-4.png"/>


### 17. What are the minimum permission needed for:
####    - Copy a directory (permission for source directory and permissions for target parent directory)

src ==> 400
dest ==> 300<br/>
<img src="./pics/17-1.png"/>

####    - Copy a file (permission for source file and and permission for target parent directory)

file ==> 400 (r--)
srcdir ==> 100 (--x)
destdir ==> 300 (-wx)<br/>
<img src="./pics/17-2.png"/>


####    - Delete a file

srcdir ==> 300 (-wx)<br/>
<img src="./pics/17-3.png"/>


####    - Change to a directory

dir  ==> 100 (--x)<br/>
<img src="./pics/17-4.png"/>


####    - List a directory content (ls command)

dir ==> 400 (r--)<br/>
<img src="./pics/17-5.png"/>


####    - View a file content (more/cat command)

file ==> 400 (r--)<br/>
<img src="./pics/17-6.png"/>


####    - Modify a file content

file ==> 200 (-w-) "non-interactive" <br/> ==> 600 "interactive"
<img src="./pics/17-3.png"/>


### 18. Create a file with permission 444. Try to edit in it and to remove it? Note what happened.

<img src="./pics/18-1.png"/>
<img src="./pics/18-2.png"/><br/>
 i can not edit but i can remove it (because of its parent usrs has permission -wx)

### 19. What is the difference between the “x” permission for a file and for a directory?

x ==> execute file 
x ==> cd on directory 
