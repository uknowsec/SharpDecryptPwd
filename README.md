# SharpDecryptPwd

## 源码项目

https://github.com/RowTeam/SharpDecryptPwd

## 简介

对密码已保存在 Windwos 系统上的部分程序进行解析,包括：Navicat,TeamViewer,FileZilla,WinSCP,Xmangager系列产品（Xshell,Xftp)。

## 使用方法

### cmd.exe

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


### Cobalt Strike

```
execute-assembly /path/to/SharpDecryptPwd.exe
```

## Reference: 
https://www.t00ls.net/viewthread.php?tid=30146&highlight=WinSCP

https://rcoil.me/2019/09/SharpDecryptPwd/
