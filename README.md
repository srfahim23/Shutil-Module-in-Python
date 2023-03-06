# Shutil-Module-in-Python
Shutil a Python module that provides a higher level interface for working with file and directories. The name "shutil" is short for shell utility. It provides a convenient and affcient way to automate task that are commonly performed on files and directories. In this repl, we'll take a closer look at the shutil module and its various functions and how they can be used in Python.

# Importing shutil
The syntax for importing the shutil module is as follows:

    import shutil

# Functions
The following are some of the most commonly used functions in the shutil module:

.shutil.copy(src, dst): This function copies the file located at src to a new location specified by dst. It the destination location already exist, the original file will be overwritten. 

.shutil.copy2(src, dst): This funciton is similar to shutil.copy, but it also preserves more metadata about the original file, such as the timestamp.

.shutil.copytree(src, dst):This funciton recursively copies the directory located at src to a new location specified by dst. It the destination location location already exist, the original directory will be merged with it.

.shutil.move(src, dst): This function moves the file located at src to a new location specified by dst. This function is equivalent to renaming a file in most cases.

.shutil.rmtree(path): This is function recursively deletes the directory located at path, along with all of its contents. This function is similar to using the rm -rf command in a shell.

Example

Here are some examples of how you can use the shutil module in your Python code:

    import shutil

    # Copying a file 
    shutil.copy("src.txt", "dst.txt")

    # Copyting a directory
    shutil.copytree("src_dir", "dst_dir")

    # Moving a file 
    shutil.move("src.txt", "dst.txt")

    # Deleting a directory
    shutil.rmtree("dir")

As you can see, the shutil module provides a simple and effcient way to perform common file and directory-related task in Python. Whether you need to copy, move, delete, or preserve metadata about files and directories, the shutil module has you covered.

In consludion, the shutil moduel is a powerful tool for automating file adn directory-related tasks in Python. Whether you are a beginner or an experienced Python, the shutil module is an essential tool to have in your toolbox.


