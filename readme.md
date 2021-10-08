


## 说明

这个游戏竟然不支持简体中文，虽然繁体也能看懂，但总归是不习惯。于是就想着给汉化了。本来是考虑替换字符串资源的，但这样以后每次更新都需要跟进，太麻烦了。后来想到替换字库来实现，方便快捷，一劳永逸。

## 原理

自制字库，将所有繁体字库中对应的字形替换为简体的，然后再使用ue4 cook，再使用ue4pack打包为pak即可。

## 预览
![](https://pic.zz173.com/auto/屏幕截图 2021-10-08 164327.png)
![](https://pic.zz173.com/auto/20211008174919.png)

## 工具

* 字库制作工具 [https://github.com/rozbo/fonts2t](https://github.com/rozbo/fonts2t)
* ue4 打包工具 [https://github.com/panzi/u4pak](https://github.com/panzi/u4pak)
* 备用打包 [https://github.com/iAmAsval/FModel](https://github.com/iAmAsval/FModel)
* 虚幻4

## 附录
Engine Version: `4.20`
AES Key: `0x61FC71A1376A29598393E2BFB976B275705F460E29399CFD1F9C060C8CD6CE40`