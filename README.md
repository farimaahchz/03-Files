# 03 Files and Finding Passwords
# Python 

Recently we found a super secret password to world domination. We wrote it down in a text file but then we lost track of it in a sea of text files. It must be somewhere in there.

Use Python's standard library to find the password

In main.py, write the following functions:



1
clean_cache: takes no arguments and creates an empty folder named cache in the current directory. If it already exists, it deletes everything in the cache folder.

2
cached_files: takes no arguments and returns a list of all the files in the cache. The file paths should be specified in absolute terms. Search the web for what this means! No folders should be included in the list. You do not have to account for files within folders within the cache directory.

3
cache_zip: takes a zip file path (str) and a cache dir path (str) as arguments, in that order. The function then unpacks the indicated zip file into a clean cache folder.

You can test this with data.zip file.

4
find_password: takes the list of file paths from cached_files as an argument. This function should read the text in each one to see if the password is in there. Surely there should be a word in there to indicate the presence of the password? Once found, find_password should return this password string.


# Skills

Importing and using Python modules;
Reading and understanding Python standard library documentation.
