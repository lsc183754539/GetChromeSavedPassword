<h1 align="center">获取谷歌浏览器保存的密码</h1>  

![python 3](https://img.shields.io/badge/Python-3.7-brightgreen.svg)
![Issues closed in about 12hours](https://img.shields.io/badge/Issues%20closed%20in-about%2012hours-brightgreen)
![Listen](https://camo.githubusercontent.com/d82e6ec0070fc8bc370c5d0881395f1c9c0483ce/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f6875692d7a2f466f726769766544422e737667)

> 获取谷歌浏览器本地保存过的Url、账号、密码等信息
  
  
* 项目变异自[DeEpinGh0st/Browser-cookie-steal](https://github.com/DeEpinGh0st/Browser-cookie-steal)的Chrome80.x，所以需要遵循的特性基本相同。

* 项目基于Python3编写，基本原理为读取本地的Chrome的sqlite文件，并使用本地的私钥做解密（所以你从别人那里拖出来的sqlite数据库文件是无法解密的）

* 你可以直接用Python3运行源码，若本地无python3环境，也可以直接[下载编译好的exe文件](https://github.com/lsc183754539/GetChromeSavedPassword/releases/tag/0.9)。
