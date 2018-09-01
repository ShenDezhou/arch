将最近使用Atom环境编写python和C的一些心得记录下来

1.Linter
===
\*nix下使用gcc，windows下MinGW工具进行C、C++代码的正确性校验的一个过程  
使用pep8可执行程序进行Python代码校验的过程

1.1MinGW Installer
---
MinGW定义：适用于Windows的极简主义GNU  
使用MinGW Installer安装mingw32-base和mingw32-gcc-g++  

1.2pep8安装
---
`pip install pep8`

2.Beautify
===
使用uncrusify对c、c++代码进行美化  

2.1uncrusify
---

下载路径
```
https://sourceforge.net/projects/uncrustify/files/uncrustify/
```

2.2uncrusify config
---
uncrusify有个非常复杂的配置文件，可以使用配置文件解析器
```
https://cdanu.github.io/uncrustify_config_preview/index.html
```
进行编辑  

2.3autopep8
---
使用autopep8对python代码进行美化
`pip install autopep8 isort`

3.ATOM插件
===
使用这两个插件linter+beautify就配置完毕了
```
https://github.com/steelbrain/linter
https://github.com/hebaishi/linter-gcc
https://github.com/bsnux/linter-python-pep8
https://github.com/Glavin001/atom-beautify
```
