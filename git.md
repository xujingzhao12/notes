## 一.git简介

## 二.基本使用

```c++
//创建一个版本仓库,找一个空目录创建比较好(不是空的也可以),在命令行直接操作创建目录或文件
mkdir test
//假设我在Git_native_repositiry目录下创建一个test目录
mkdir /e/Git_native_repositiry/test
//先要进入这个目录
cd test
//将test变为仓库,然后这test下会多出一个.git文件夹(可能被隐藏,是配置相关信息,不要修改)
git init
//在该仓库添加一个hello.txt文件,内容为hello,然后放入暂存区(add可以同时操作几个文件)
git add hello.txt//git add hello.txt abc.txt bbb.txt
//将暂存区的内容添加到本地仓库(commit可以一次提交多个暂存区内容)
git commit -m "第一次添加到本地仓库"//-m后是添加说明,便于以后知道自己改了什么
//在将代码放入远程仓库(可以是公司自己的),比如放到github上




```

