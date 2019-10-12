# SharpDecryptPwd

## 简介

昨天看到[Rcoil](https://rcoil.me)师傅的文章[SharpDecryptPwd](https://rcoil.me/2019/09/SharpDecryptPwd/)
给出了实现思路，但是没有给出代码，所以自己跟着文章写了一个。
对密码已保存在 Windwos 系统上的部分程序进行解析

## 使用方法

```
> SharpDecryptPwd.exe

Author: Uknow
Github: https://github.com/uknowsec/SharpDecryptPwd
Reference: https://rcoil.me/2019/09/SharpDecryptPwd/

Usage: SharpDecryptPwd.exe -NavicatCrypto
       SharpDecryptPwd.exe -TeamViewer
       SharpDecryptPwd.exe -FileZilla
       SharpDecryptPwd.exe -WinSCP
       SharpDecryptPwd.exe -Xmangager -p Session_Path
```

```
> SharpDecryptPwd.exe -TeamViewer
```
![](https://github.com/uknowsec/SharpDecryptPwd/blob/master/Teamviewer.png)

```
> SharpDecryptPwd.exe -NavicatCrypto
```
![](https://github.com/uknowsec/SharpDecryptPwd/blob/master/NavicatCrypto.png)


```
> SharpDecryptPwd.exe -FileZilla
```
![](https://github.com/uknowsec/SharpDecryptPwd/blob/master/FTP.png)

```
> SharpDecryptPwd.exe -Xmangager -p D:\xshell\Xshell\Sessions
```
![](https://github.com/uknowsec/SharpDecryptPwd/blob/master/Xshell.png)

## Reference: 
https://www.t00ls.net/viewthread.php?tid=30146&highlight=WinSCP
https://rcoil.me/2019/09/SharpDecryptPwd/
