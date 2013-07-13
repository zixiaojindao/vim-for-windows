###安装方法
* copy所有文件，目录到vim安装根目录下，覆盖所有存在文件。
* 增加tools到环境变量Path。
* 如果安装路径不是默认的，请修改vimrc文件中pydiction\_location。

###基本特性
* supertab: tab键自动补全
* taglist: 快捷键tl
* winmanager: 快捷键wm
* python语法，自动补全
* ctags & cscope: F12生成tags and cscope需要的文件
* nerd\_comment: header为","。
    * ,ca，在可选的注释方式之间切换，比如C/C++ 的块注释/* */和行注释//
    * ,cc，注释当前行
    * ,c，切换注释/非注释状态
    * ,cs，以”性感”的方式注释
    * ,cA，在当前行尾添加注释符，并进入Insert模式
    * ,cu，取消注释
