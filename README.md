# Hello-world-LKM
LKM to display a simple message in the kernel log.

Compile and Load:
```
root@kali:~# git clone https://github.com/b4sh0x1/Hello-world-LKM
root@kali:~# cd Hello-world-LKM
root@kali:~# make
root@kali:~# insmod hello.ko
root@kali:~# tail -n2 /var/log/kern.log
```
