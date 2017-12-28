# test2
second test


## Git Command:
 pwd:
ls
<br/>
1. 命令格式：
<br/>
ls [选项] [目录名]
<br/>
2. 命令功能：
<br/>
列出目标目录中所有的子目录和文件。
<br/>
3. 常用参数：
<br/>
-a, –all 列出目录下的所有文件，包括以 . 开头的隐含文件
<br/>
-A 同-a，但不列出“.”(表示当前目录)和“..”(表示当前目录的父目录)。
<br/>
-c  配合 -lt：根据 ctime 排序及显示 ctime (文件状态最后更改的时间)配合 -l：显示 ctime 但根据名称排序否则：根据 ctime 排序








## Git 克隆现有的仓库
<br/>
Git clone [ url ].  Eg: $ git clone  https://github.com/ChyweiChen/Assignment-of-OPP
<br/>
如果想要在克隆远程仓库的时候自定义本地仓库，可使用以下命令：
<br/>
$ git clone https://github.com/ChyweiChen/Assignment-of-OPP mygit-start  
<br/>
本地克隆的仓库就变为mygit-start

## 检查当前配置信息：
<br/>
$ git config  --list

## 在现有的目录中初始化仓库
$ git init

## 添加跟踪文件file，（把文件file放入暂存区）
$ git add file

## 提交
$ git commit -m “some message”

## 文件状态预览
$ git status

## 文件详细状态预览（可预览文件具体修改了哪个地方）
<br/>
$git diff 
<br/>
Note：git diff 只显示尚未暂存的改动

## 删除文件file（会在暂存区和电脑磁盘中删除该指定文件）
$git rm file


## 强制删除文件file（会在暂存区和电脑磁盘中删除该指定文件）
$git rm -f file


## 删除文件file（只在暂存区移除文件file，该文件还在电脑磁盘里）
$git rm --cached file


## 查看提交历史
$git log

## 撤销操作
--amend

## 取消文件file暂存(作用类似于 $git rm -- cached file)
$git reset HEAD file

## 撤销对文件file的修改
$git checkout -- file

## 添加远程仓库
Eg: Add a remote whose address is https://github.com/ChyweiChen/test  and name it firstremote
<br/>
$git remote add firstremote https://github.com/ChyweiChen/test

## 查看已配置的远程仓库
$git remote

## 查看远程分支
$git remote show [remote name]



