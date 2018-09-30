# Lua 环境安装

### Linux 系统上安装

Linux & Mac上安装 Lua 安装非常简单，只需要下载源码包并在终端解压编译即可，本文使用了5.3.0版本进行安装：  


```text
curl -R -O http://www.lua.org/ftp/lua-5.3.0.tar.gz
tar zxf lua-5.3.0.tar.gz
cd lua-5.3.0
make linux test
make install
```

### Mac OS X 系统上安装

```text
curl -R -O http://www.lua.org/ftp/lua-5.3.0.tar.gz
tar zxf lua-5.3.0.tar.gz
cd lua-5.3.0
make macosx test
make install
```

接下来我们创建一个 HelloWorld.lua 文件，代码如下:

```text
print("Hello World!")
```

执行以下命令:

```text
$ lua HelloWorld.lua
```

输出结果：

```text
Hello World!
```

### Window 系统上安装 Lua

window下你可以使用一个叫"SciTE"的IDE环境来执行lua程序，下载地址为：

* Github 下载地址：[https://github.com/rjpcomputing/luaforwindows/releases](https://github.com/rjpcomputing/luaforwindows/releases)
* Google Code下载地址 : [https://code.google.com/p/luaforwindows/downloads/list](https://code.google.com/p/luaforwindows/downloads/list)

双击安装后即可在该环境下编写 Lua 程序并运行。

你也可以使用 Lua 官方推荐的方法使用 LuaDist：[http://luadist.org/](http://luadist.org/)



### Cloud Studio {#cs-lua}

[Cloud Studio](https://studio.coding.net/) 是基于浏览器的集成式开发环境，支持绝大部分编程语言，包括 HTML5、PHP、Python、Java、Ruby、C/C++、.NET 等等，无需下载安装程序，一键切换开发环境。 [Cloud Studio](https://studio.coding.net/) 提供了完整的 Linux 环境，并且支持自定义域名指向，动态计算资源调整，可以完成各种应用的开发编译与部署。

![](https://dn-coding-net-production-pp.qbox.me/1a0d4ed6-cd32-4e60-bad2-e6140fa556cb.png)

