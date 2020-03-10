# Linux Basic

## A few shortcuts

- `ctrl + alt + T` - Open terminal
- `ctrl + alt + <up/right/left>` - Switch workspace
- `ctrl + alt + shift + <right/left>` - Move current window to right/left workspace
- `ctrl + alt + <F1/F2/F3/F4/F5/F6>` - Open TTY login (does not use GUI)
- `ctrl + alt + <F7>` -  Leave TTY screen and switch to GUI
- `<up/down>` - Move back/forth the previously typed terminal commands

## Basic commands

```shell
$ pwd       # path of working directory
$ ls        # list the contents of current directory
$ cd Music  # changes the current directory to `Music` directory
$ cd ..     # change the directory to one level up except at '/'
$ cd -      # jumps to previous `pwd` before a `cd`
$ ls -l     # long listing the file
$ ls -lrt   # list file based on the modified date. recent at the last.
$ man ls    # list manual pages for  `ls`
$ ls --version # shows the version of `ls`. Sometimes it is `<cmd> -v`
```

- `pwd`       - path of working directory
- `ls`        - list the contents of current working directory i.e `pwd`
- `cd folder` - changes the current directory to `folder`
- `cd ..`     - change the directory to one level up except at '/'
- `cd -`      - jumps to previous `pwd` before a `cd`
- `ls -l`     - long listing of file/folder
- `ls -lrt`   - list file based on the modified date. recent at the last
- `man <cmd>`       - list manual pages for any valid linux `cmd`
- `<cmd> --version` - shows the version of valid `cmd`






