title: c++filt - Demangle C++ and Java symbols
date: 2015-10-22 17:02:29
tags: [技术笔记,c++]
---
c++filt:
.so undefined symbol _ZN3FooD2Ev

``` bash
$ c++filt _ZN3FooD2Ev
Foo::~Foo()
```
