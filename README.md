19CS416-CS-Ex-3-Linux-Commands
NAME : PRAVEENA D
REG NO : 212224040248
Linux is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

19CS416-CS-Ex-3b-Kali linux
Procedure:
Go to the Website: Visit the official site at https://www.kali.org.

Click “Download”: On the homepage, click the “Download” button or go to https://www.kali.org/get-kali/.

Choose Version: Select the version you need (Installer, Live, or Virtual Machine), and choose 64-bit or 32-bit.

Download ISO/VM Image: Click to download the ISO file or pre-built VirtualBox/Vmware image.

Verify & Save: (Optional but recommended) Use the SHA256 hash to verify the file, then save it to your system.

Linux Commands
Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

1. ls Command
The ls command is used to display a list of contents in a directory.

Syntax:

ls
Output: 427555018-76dc10ce-a94f-4aee-8f9f-adcc903b5050

2. pwd Command
The pwd command displays the location of the current working directory.

Syntax:

pwd
Output: 427555536-92e82e0c-8b68-47bc-bd36-6302eef18fe1

3. mkdir Command
The mkdir command is used to create a new directory.

Syntax:

mkdir <directory_name>
Output: 427555788-a07bbcfe-8b5c-4054-9728-bcb375711b13

4. rmdir Command
The rmdir command is used to delete a directory.

Syntax:

rmdir <directory_name>
Output: 427555941-39e68300-cdf3-44b8-9c70-49e0ed80daed

5. cd Command
The cd command is used to change the current directory.

Syntax:

cd <directory_name>
Output: 427556261-0b6dfbda-a084-43ab-a3b9-564e89f8fe2a

6. cat Command
The cat command is used to create, display, and concatenate files.

Syntax:

cat [OPTION]... [FILE]...
**Output 427556469-5308059e-c8dc-4374-ba23-e151ed62c6ff

:**

7. cp Command
The cp command is used to copy files or directories.

Syntax:

cp <source_file> <destination_file>
Output 427556965-03783054-48fe-4af5-96f8-b9b178671f03 ut:

8. gedit Command
gedit is a general-purpose text editor used to create and edit text files.

Syntax:

gedit <file_name>
Output: 427557185-f6122908-5022-41d5-8b5e-92bcbc93217e

9. su Command
The su command provides administrative access to another user.

Syntax:

su <username>
Output:

10. mv Command
The mv command is used to move a file or directory from one location to another.

Syntax:

mv <file_name> <directory_path>
Output:

11. rename Command
The rename command is used to rename files.

Syntax:

rename 's/old-name/new-name/' <files>
**Output: 427557863-08db1911-3afc-48cf-8230-8e44068bbc43 **

12. head Command
The head command displays the first 10 lines of a file.

Syntax:

head <file_name>
**Output: 427558050-414fa66f-dacc-4ce7-bf63-787bab95011f **

13. tail Command
The tail command displays the last 10 lines of a file.

Syntax:

tail <file_name>
Output 427558265-c168d024-e903-4499-b898-4271c94c3b7a put:

14. id Command
The id command displays the user ID (UID) and group ID (GID).

Syntax:

id
Output: 427558265-c168d024-e903-4499-b898-4271c94c3b7a

15. grep Command
The grep command is used to search for a pattern within files.

Syntax:

command | grep <search_word>
Output: 427559133-6066c8b7-957a-410d-a263-8bc1d6a73260

16. tr Command
The tr command is used to translate or delete characters.

Syntax:

command | tr <old> <new>
Output: 427559481-4dca4667-6b53-4c51-8cec-5b066b73dacc

17. chmod Command
The chmod command is used to change the access mode (permissions) of a file.

Syntax:

chmod <options> <permissions> <file_name>
Output: 427589521-d9bd5603-b7ac-405b-8167-40d01e8aeceb

18. tar Command
The tar command is used to create or extract archive files.

Syntax:

tar [options] [archive-file] [files_to_archive]
Output: 427589685-e16f7228-596c-4940-a73a-0049e484964b

19. chown Command
The chown command is used to change the ownership of a file.

Syntax:

chown <owner_name> <file_name>
Output: 427560793-d9bca3d1-65d2-478a-9fd6-949b225f7550

20. make Command
The make command is used to build and maintain groups of programs.

Syntax:

make [-f makefile] [options] [targets]
Output: 427561184-d69d155c-369f-4b9c-bac2-75ad270ee4cf

21. ifconfig Command
The ifconfig command is used to configure network interfaces.

Syntax:

ifconfig [options] [interface]
Output:

22. chmod 777 Command
The chmod 777 command gives read, write, and execute permissions to the owner, group, and others.

Syntax:

chmod 777 <file_name>
chmod -R 777 /path/to/file/or/folder
Output: 427561752-8a825258-4673-46f7-83e5-47290977bc73 *

23. host Command
The host command is used to display the IP address for a given domain name.

Syntax:

host <domain_name> or <ip_address>
Output 427562064-8b41db02-b3af-4055-932b-7ca1851c46e2 :

24. gzip Command
The gzip command is used to compress files, replacing the original file with a compressed one with a .gz extension.

Syntax:

gzip <file1> <file2> <file3>...
Output: 427562337-9d51f888-f806-49db-9a63-3bf7c3d43643

25. sort Command
The sort command is used to sort the contents of a file alphabetically.

Syntax:

sort <file_name>
Output: 427562590-d1086111-de23-4328-b41a-65933b77edbe

26. cal Command
The cal command displays the current month's calendar with the current date highlighted.

Syntax:

cal
Output:427562890-5fe4509f-5f8d-4ebb-9db8-bf5d86836c96

27. clear Command
The clear command clears the terminal screen.

Syntax:

clear
Output: 427589856-ead26219-dc40-4ae9-ac3b-831aa8d4364e

28. mail Command
The mail command is used to send emails from the command line.

Syntax:

mail
Output 427563388-f03383cc-f03b-4a6c-8a9d-e37363a1ed4a t:**

29. df Command
The df command displays the disk space usage of file systems.

Syntax:

df
Output: 427563853-16492388-8cc1-4dbe-9e68-085b6c794fa1

30. find Command
The find command is used to search for files in a directory hierarchy.

Syntax:

find <directory> -name <file_name>
Output: 427564107-a097b498-efbc-484b-8f20-7c1335635f6c

Result
Successfully performed the series of Linux commands as specified.
