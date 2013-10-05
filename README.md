###停止更新
适用于windows和linux的vim配置请参考[vimconfig](https://github.com/zixiaojindao/vimconfig)
本版本库弃用
###安装方法
* copy所有文件，目录到vim安装根目录下，覆盖所有存在文件。
* 增加tools目录到环境变量Path。

###基本特性
* NERDTree: 快捷键nt
* minibuffer: 快速切换缓冲区
* supertab: tab键自动补全
* taglist: 快捷键tl
* ctags & cscope: F12生成tags and cscope需要的文件
    * 已经在$VIM/tags添加了c++的标准库tags
* NERD\_comment: header为","
    * ,ca，在可选的注释方式之间切换，比如C/C++ 的块注释/\* \*/和行注释//
    * ,cc，注释当前行
    * ,c，切换注释/非注释状态
    * ,cs，以”性感”的方式注释
    * ,cA，在当前行尾添加注释符，并进入Insert模式
    * ,cu，取消注释
* Calendar: 快捷键ca,按住&lt;Up&gt;, &lt;Down&gt;切换年份，&lt;Left&gt;, &lt;Right&gt;切换月份。
* xml.vim, html.vim: 提供xml, html的快速编辑。
* python语法，自动补全
* 编译c,c++:下载mingw,添加mingw的bin目录到path，&lt;F5&gt;可以编译单文件,&lt;F6&gt;可以make
