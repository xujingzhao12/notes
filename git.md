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
//在该仓库添加一个hello.txt文件,内容为hello
git add hello.txt



```

