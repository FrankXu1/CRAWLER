# Problems

## 1.
import pyquery，报错ImportError: DLL load failed  
报错其实是from lxml import etree这一句  
lxml这个包是我pip install pyquery时自动安装的。卸载pip uninstall lxml重新安装pip install lxml仍然报错！  
于是下载了一个旧版本的whl，lxml-3.7.3-cp36-cp36m-win_amd64.whlC:\windows\system32>pip uninstall lxml  
链接：https://www.jianshu.com/p/98aacbbcfe08  


## 2.
