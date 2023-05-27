# Brief Reference Cmd
Brief reference of the Cmd.

---

#### Show the list of commands
```
> help
```

#### Show the help of a command
```
> help <command>
```

#### List the files of the current directory
```
> dir
```

#### Change directory
```
> cd <dir>
```

#### Change to the parent directory
```
> cd ..
```

#### Print the current date
```
> date
```

#### Show the current volume information
```
> vol
```

#### Show the enviroment variables
```
> echo %path%
```

#### Show the system info
```
> systeminfo
```

#### Show the tmp directory
```
> echo %tmp%
```

#### Print the current directory tree
```
> Tree . /F
```

#### Redirect text to a file
```
> echo This is a simple file >> file.txt
```

#### Get the processor architecture
```
> echo %processor_architecture%
```

#### Open the file explorer
```
> explorer
```

#### Enter to a directory that has space between words
```
> cd "files in the system"
```

#### Move the content of one directory tree into another
```
> robocopy /move /e sourcedir destdir
```

#### Create a tar file
```
> tar -zcvf tar-archive-name.tar.gz source-folder-name
```

### Exit from the cmd
```
> exit
```

#### Print the current directory path
```
> cd
```

#### Create an empty file
```
> type nul > your_file.txt

NOTE: This will create a 0 bytes in your_file.txt


> echo.> your_file.txt

NOTE: "echo." will create a file with one empty line in it.


> call >> your_file.txt

NOTE: Calls one batch program from another without stopping the parent batch program.
```

#### Disable all shared folders
```
1. Run cmd as administrator.

2. > wmic path Win32_Share delete
```

#### Show the cmd in fullscreen
```
Alt + ENTER
```

#### Clear the screen
```
> cls
```

#### Show the current time
```
> time
```

#### Verify connectivity to a server
```
> ping <targetname>
```
