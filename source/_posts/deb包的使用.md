title: deb包的使用
date: 2015-10-30 15:07:06
tags: [技术笔记,linux]
---

查看deb包文件内容
```
  dpkg-deb -c packageName
```


checkinstall 生成deb文件
```
  sudo checkinstall
```
checkinstall 根据Makefile中的make install生成deb文件
 

