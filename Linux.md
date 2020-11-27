# Linux commands

## For editing a project inside the folder
```/var/www```


To make the folder editable inside ```/var/www``` type the following command...

```sudo chown -R jugalkdas:www-data /var/www/"The folder you want" && chmod -R g+sw /var/www/"The folder you want"```

## File and folder commands in linux terminal

### (noob commands)

```pwd```

This command displays the present working directory where you are currently in.

```ls```

This command will list the content of a directory.

```ls -la```

This command will list all the content of a directory including the hidden files and directories.

```mkdir folder-name```

This command will create a new directory(only one directory), provided it doesn't exists.

```mkdir -p new/new-folder/folder-name```

This command will create nested directories, like shown above.

```rmdir folder-names```

This command will remove/delete an existing directory.

```cd /directories/directory-name/```

This command is used to change directory.

```touch filename.txt```

This command will creates a new file.

```rm filename.txt```

This command will delete a file.

```rm -f filename.txt```

This command forcefully deletes a file.

```rm -r /directories/directory-name/```

This command deletes a directory recursively along with its content.

```rm -rf /directories/directory-name/```

This command forcefully and recursively deletes a directory along with its content.

```cp file1 file2```

This command copies the content of file file1 into file file2.

```cp -r dir1 dir2```

This command copies the content of directory dir1 into directory dir2.

```mv``` rename files and directories

We can use ```mv``` command to rename files and directories.

examples -

```mv hello.txt hi.txt```

```mv awesome superawesome```



```cat filename.txt```

This will print the content of a file.

```head filename.txt```

This command will print the first 10 lines of a file.

```tail filename.txt```

This command will print the last 10 lines of a file.

```tail -f filename```

This will print the last 10 lines of a file and will keep printing new lines as they get appended to the file.

```ln -s /another/directory /to-another/directory```

This will link a directory to another.
