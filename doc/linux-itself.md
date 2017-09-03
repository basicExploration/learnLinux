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
