0: [pwd] prints the absolute path of the working directory

1: [ls] lists directory contents

2:[cd] changes directory

3: [ls -l] lists directory contents in long form

4: [ls -la] lists directory contents in long form, including hidden files

5: [ls -na] Display current directory contents in long format with user and group IDs displayed numerically and hidden files (starting with .)

6: [mkdir /tmp/my_first_directory] Creates a my_first_directory directory inside the tmp directory

7: [mv /tmp/betty /tmp/my_first_directory/betty] Moves file betty, which is located inside the tmp directory, to the my_first_directory directory, which is also located inside the tmp directory.

8: [rm /tmp/my_first_directory/betty] Removes file betty located in tmp/my_first_directory directory.

9: [rmdir /tmp/my_first_directory] Removes directory my_first_directory located in directory tmp.

10: [cd -] Changes directory to the previous directory you were in.

11: [ls -la . .. /boot] List all files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of workingdirectory, and /boot directory. 

12: [file /tmp/iamafile] Prints the type of file iamafile.

13: [ln -s /bin/ls __ls__] Create a symbolic link named __ls__ for /bin/ls

14: [cp -u *.html ..] Copies all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.
