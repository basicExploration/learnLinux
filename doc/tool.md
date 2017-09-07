# 一些工具

## [目录](./summary.md)

- ## 这些命令有
    - type显示某个命令的用法

    - which显示某个文件的安装位置

    - apropos显示比较合理的后续的命令猜测

    - info显示info命令

    - whatis显示一个命令的简单简洁

    - alias创建命令的别名
- ## type

    - 用法：`type command`会显示出来某个命令的具体类型。
    ```bash
    type cd
    # cd is a shell builtin
    ```
    所以也就是说type是可以显示命令类型的命令
- ## which

    - which含义就是显示某个文件所在的位置

    - 用法：`which somefile`

    - which不对别名起作用

- ## help

    - help就是帮助你看到每个命令的命令参数

    - help用法`help commond`

    ```bash
    help cd
    # cd: cd [-L|-P] [dir]
    # Change the current directory # to DIR.  The variable $HOME is # the
    # default DIR.  The variable # CDPATH defines the search path # for
    # the directory containing DIR.  # Alternative directory names in # CDPATH
    # are separated by a colon (:).  # A null directory name is the # same as
    # the current directory, i.e. # `.'.  If DIR begins with a # slash (/),
    # then CDPATH is not used.  If # the directory is not found, # and the
    # shell option `cdable_vars' is # set, then try the word as a # variable
    # name.  If that variable has a # value, then cd to the value of # that
    # variable.  The -P option says # to use the physical directory # structure
    # instead of following symbolic # links; the -L option forces # symbolic links
    # to be followed.

    ```
    - 注意表示法：出现在命令语法说明中的方括号，表示可选的项目。一个竖杠字符 表示互斥选项。后面的dir表示可能出现的选项例如一个路径等等。

    - 有些命令可以直接使用`commond --help`来使用不过并不是所有的命令都有要注意了。

## [目录](./summary.md)