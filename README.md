# how-to-check-storage-of-folder-and-sub-folder-linux
how to check storage of folder and sub folder linux

If you want to check the storage space used by a particular folder and its subfolders in Linux, there are two common commands that you can use: df and du.

The df command is used to display the amount of disk space used and available on your file system. By default, it shows the usage for all mounted file systems, but you can limit the output to a specific directory by using the -h option followed by the directory path. For example, if you want to check the storage space used by the "/home" directory and its subdirectories, you can use the command `df -h /home`. This will display the total, used, and available disk space in a human-readable format.

On the other hand, the du command is used to estimate the disk space usage of a specific file or directory. By default, it displays the disk space used by the specified directory and all of its subdirectories. To check the storage space used by a particular folder and its subfolders, you can use the command `du -sch /folder`. This will display the total disk space used by the folder and all its subdirectories, along with a summary at the end.

In summary, if you want to check the storage of a folder and its subfolders in Linux, you can use the df command to check the total disk space usage of the file system where the folder is located, and use the du command to estimate the disk space usage of the folder and its subdirectories
