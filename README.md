# Python copy files from one location to another

                                                 Python shutil.copy()method:

   The shutil.copy() method in Python is used to copy the files or directories from the source to the destination. The source must represent the file, and the destination may be a file or directory.

This function provides collection and operations on the files it also helps in the copying and removal of files and directories.

                                                   Description
In this example, I have imported two modules called shutil, and os this module helps in automating the process of copying and removing files and directories.

We have to write a path for both source and destination. We have to use shutil.copyfile(source, destination) to copy the file from source to destination. Along with the path, the name of the file with its extension should be written.

source= r'D:\Newfolder\filename.txt' is the source path. name.txt is the filename that I have created with the .txt extension.

destination = r'E:\filename.txt' is the destination path. Here, I have created a folder called Newfolder to copy the file name.txt in the Newfolder.
