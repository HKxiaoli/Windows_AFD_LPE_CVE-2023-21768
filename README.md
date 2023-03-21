# CVE-2023-21768 Local Privilege Escalation POC

authors: [chompie](https://twitter.com/chompie1337) & [b33f](https://twitter.com/FuzzySec)

复现文章:[hlingxbm](https://hlingxbm.blog.csdn.net/article/details/129686960?spm=1001.2014.3001.5502)

For demonstration purposes only. Complete exploit works on vulnerable Windows 11 22H2 systems. 
Write primitive works on all vulnerable systems.

Usage:

```
Windows_AFD_LPE_CVE-2023-21768.exe <pid>
```

where `<pid>` is the process ID (in decimal) of the process to elevate.

Should result in the target process being elevated to SYSTEM



The I/O Ring LPE primitive code is based on the I/ORing R/W [PoC](https://github.com/yardenshafir/IoRingReadWritePrimitive) by [Yarden Shafir](https://twitter.com/yarden_shafir)

Blog post soon, will update repo when it's released.

![image](https://img-blog.csdnimg.cn/75596bd32cb44e3c8673c040015a27de.png)