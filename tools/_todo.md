#### todo
1. vtune性能测试工具
1. http://linuxperf.com/?p=102
```
磁盘锁的实现原理,使用方法，优缺点
WARNING REMOTE HOST IDENTIFICATION HAS CHANGED, 在使用mobaXterm的原有标签连接新安装的主机是出现这个提示
Unfortunately, interactive shells are disabled. 在使用git时出现以上报错，interactive shell 还可以disable么
当进程文件删除之后，gdb挂载之后，为什么无法查看线程？

https://git-scm.com/book/en/v2/Git-Internals-The-Refspec 了解一下
ansible工具了解下
命令ipcs了解一下
命令mtr了解一下
strace man 手册

tmux卡死问题，client和server都只有一个线程，用tmux kill-window -t 1 终止该window。

sshpass 做什么用的？
添加sudo权限通过wheel方式和编辑sudoers的方式哪个更好？
shutdown命令的halt是什么意思？
the /run/nologin file is created to ensure that further logins shall not be allowed. (ref shutdown)
https://www.ibm.com/developerworks/cn/linux/l-bash-test.html
windows10 下有ubuntu子系统，可以试用下，尽管据说有不少命令可能还不能用。

lowest priority APIC routing
如果查看占用CPU高的程序？
cat /sys/block/sda/queue/read_ahead_kb
echo c > /proc/sysrq-trigger
/proc/net/dev
/proc/net/snmp    
ifdown和ifconfig区别？

https://stackoverflow.com/questions/12600330/pop-back-return-value
http://www.gotw.ca/gotw/008.htm
https://stackoverflow.com/questions/596162/can-you-remove-elements-from-a-stdlist-while-iterating-through-it
https://stackoverflow.com/questions/799314/difference-between-erase-and-remove
```

#### done
```
网络丢包模拟工具tc(done)
logrotate基本用法(done)
excel锁定一行(done)
什么是 UP Machine (done) UP就是uniprocessor, 单处理器
vfs_cache_pressure对dentries和inode对象的释放影响了解一下（done）
atop中的slab内存了解一下(done)
内存泄露工具Valgrind了解(done, 20200606)
tab键自动补全的机制（done）
自动补全的原理(done, 20200604）
/proc/locks是什么(done, 20200710)
```
