1. Open Command prompt by using the shortcut `Windows+R`

2. Type the command keyword as below
```
cmd
```

3. The above action will take you to the root folder in your local machine
4. Go to the folder where you saved the git repositories with the below command
```
cd <foldername/structure>
```

5. Type the `code` keyword to open the folder structure in VSCode
```
Code <FolderName/Structure>
```
6. The above step will open your folder in VSCode application
7. Once you get into VSCode application, you are required to: 
   7.1: Pull the server data into your local machine using 'Pull' command and 
   7.2: check if the data present in the Git Server matches with you local reporitory (in your machine) by using the below `status` command
```
git status
```
8. To view the list of files in the present directory, type-in the `list` command as below
```
ls
```
9. Get into the intended file by using the shortcut `Ctrl+P`
10. Type the file name that you want to edit and click `Enter`
11. Make all the necessary changes and save using `Ctrl+s`
12. To view the modified/created files/directories, us the below command
```
git status
```
13. Now, you will see all the `modified files` in Red color (as it has not been added to commit yet)
14. In case you want to compare all the local changes with git repository in server, use the below command
```
git diff
```

*   In case you want to compare `only a file_1` with server

```
git diff file_1
```

* For multiple file comparisions

```
git diff file_1 file_2 file_3
```
15. Upon final review, you can now add the created/modified/deleted files/directories to `commit` by using the below command
```
git add .
```
16. The above command is only recommendable when you are sure to add all the changes that you made to the commit. However, if you want to add only the changes you made to few files/directories, you can speficy each change by using the following command
```
git add foldername\file_1 file_2 folder\file_3
```
17. Before pushing the added changes to the git server, you are required to commit the changes by using the below command and can also mention the message for future reference
```
git commit -m "<Your message here>"
```
18. The final step to update git server from your local machine is to use `push` command as mentioned below
```
git push
```


    *   Other useful commands
        1. cd <foldername> - Opens up the given folder
        2. cd .. - To return to 1 folder back
        3. cd ..\.. - To return to 2 folders back
        4. mv - To Move the file from one folder to another
        5. mv - Also to rename the file
        6. cp - Copies the files and paste it in another folder (syntax: cp <source> <target>)
        7. cat - Shows the contents of the specified file (syntax: cat foldername\filename)
        8. cat > - Creates a new file under the given folder (syntax: cat >foldername\filename)
        
