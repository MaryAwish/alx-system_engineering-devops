SHELL BASICS TASKS

Exercise 0: pwd === print working directory

Exercise 1: ls === list directory contents

Exercise 2: cd === change directory

Exercise 3: ls -l === list directory contents in long form

Exercise 4: ls -la === list directory contents in long form, including hidden files

Exercise 5: ls -la Note: Are files inherently ordered

Exercise 6: mkdir /tmp/my_first_directory Create a my_first_directoty directory inside the tmp directory

Exercise 7: mv /tmp/betty /tmp/my_first_directory/betty Move file betty, which is located inside the tmp directory, to the my_fist_directory directory, which is also located inside the tmp directory. This exercise required some dir traversing.

Exercise 8: remove file betty

Exercise 9: remove directory my_first_directory from tmp

Exercise 10:cd - change directory to previous directory

Exercise 11: ls -la . .. /boot List all files/directories, including hidden files/directories, from 3 separate directories: current directory, parent of working directory, and /boot directory. The ls command allows multiple directories to be listed separated by spaces.
Exercise 12: file /tmp/iamafile Prints the type of file iamafile.

Exercise 13: ln -s /bin/ls ls Create a symbolic link named ls for /bin/ls

Exercise 14: cp -u *.html .. Copy all html files from the current directory to the parent directory, but only copy files that didn't exist in the parent directory or are newer versions than the ones that already exist in the parent directory. The -u option didn't show on the terminal manual page. The -u option copies the file into the directory if its a newer version. If the file doesn't exist in the directory, it will copy over. The -n option works for copying files that don't exist in the parent directory, but it doesn't check if the file is a newer version or not.

Exercise 15: mv [[:upper:]]* /tmp/u Move all files that begin with a capital letter to /tmp/u

Exercise 16: rm *~ Deletes all files in the current directory that end with a ~

Exercise 17: create a directory inside a directory inside a directory mkdir -p welcome/to/school

Exercise 18: ls -pam List all files and directories of the current directory, separated by commas. Directory names should end with a /. The listing should be alph ordered, except for dot (.) or dot dot (..), which should be listed at the beginning. The -a option is to show any hidden files. The -p option writes a / at the end of directory names. The -m option streams the output, separating each listing with commas.

Exercise 19: using vi editor create file schoo.mgc which contains 0 string SCHOOL School data and !:mime School then on the terminal file -C -m school.mgc. A cool thing to note is that the file command is compiling and running the magic file. So there is no need to compile to magic "permanently". NOTE: Compiling a magic source file: $ file -C -m .mgc This produces the compiled magic file. $ file -i -m .mgc * This allows you to use the compiled file by specifying its name using the -m switch again.

