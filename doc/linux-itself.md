# 探究Linux本身的很多特性
- 重点详细介绍ls,file,less这三个命令。
## ls
- `ls - a`刚才已经介绍过了是为了打开隐藏的文件。
- 你可以打开任意的目录`ls /bin`这样也是可以的。
>   
    /Users/thomashuke/Desktop:
    code

    /bin:
    [		df		launchctl	pwd		test
    bash		domainname	link		rm		unlink
    cat		echo		ln		rmdir		wait4path
    chmod		ed		ls		sh		zsh
    cp		expr		mkdir		sleep
    csh		hostname	mv		stty
    date		kill		pax		sync
    dd		ksh		ps		tcsh
    thomasdeMacBook-Air:~ thomashuke$ 
- `ls -l`长模式输出
    > 也就是说会显示一大堆的文件---显示全部的信息。
- `ls -lt`意思就是短选项l和短选项t同时作用这里就要说明了
    > linux中有短选项和长选项例如-就是短选项--version就是长选项，长选项的缩写就是短选项例如`--verision => -v`并且linux中短选项可以同时写`-lt`就是`-l -t`的缩写。
- ls常用命令集锦：
    ![pic](../picture/2017-9-4.png)
    > 由图可以看出来长选项几乎都有可以对应的短选项，使用的时候要注意如果有短选项就使用短的就好，没有在使用长选项 （英语：opinions）
---
## file功能
- file命令返回文件类型
- `file fileName`
- 一个简单的显示举例
    ```bash
    file README.md

    // UTF-8 Unicode text
    ```
---
## less命令
- less的含义是浏览文本
- 退出不使用esc不使用control+c
- 退出使用`q`即可
    ```bash
    q

    //为了明显我刻意单列出来
    ```
- less命令：![p](../picture/2017-9-4-1.png)
- 关于Linux或者说类unix中一些常用的路径到总结，大部分是如此，但是不排除有特殊情况：<br><br>![d](../picture/long.gif)
---
## 软硬链接
