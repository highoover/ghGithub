# ghGithub

# 王顶_Github开源之旅

## 第一季启程

### 1.教程资料
https://github.com/wangding/courses/tree/master/github

### 2.git桌面工具
①git官网下载

②git --version命令难是否成功

③设置Git Bash环境

- 光标颜色由白色改成：绿色

- 光标开头由下划线改成：块状

- 光标闪烁改成：不闪

- 字体改成14号或16号

- 字体集改成UTF-8（支持中文）

- 重新进入Git Bash环境

### 3.Bash命令体验
cd、mv、mkdir、cp、pwd、rm

### 4.设置Git参数
①显示当前的Git配置

git config --list

②设置提交仓库时的用户名信息

git config --global user.name "highoover"

③设置提交仓库时的邮箱信息

git config --global user.email "gaohao323@sina.com"

### 5.git结构
①workspace（工作区）

②index/stage（暂存区）

③repository（仓库区或本地仓库）

### 6.新建代码仓库
①在当前目录下（不要中文）新建一个Git代码库
git init
②下载一个项目和它的整个代码历史
git clone [url]
[url]格式为https://github.com/[userName]/reposName
### 7.添加和删除文件
①添加指定文件到暂存区
git add [file1] [file2]
②删除工作区文件，并且将这次删除放在暂存区
git rm [file1] [file2]
③改名文件，并且把这个改名放入暂存区
git mv [file-origin] [file-rename]
### 8.代码提交
①提交暂存区到仓库
git commit -m [message]
②直接从工作区提交到仓库（该文件在仓库中有历史版本）
git commit -a -m [message]
### 9.查看信息
①显示变更信息
git status
②显示当前分支的历史版本
git log
git log ---oneline
### 10.查看某一版本内容
git show [hash数字]
### 11.同步远程仓库
①增加远程仓库并命名
git remote add [shortname] [url]
②交本地的提交推送到远程仓库
git push [remote] [branch]
③将远程仓库的提交下拉到本地
git pull [remote] [branch]
### 12.在线练习Git
https://try.github.io/
13.闯关练习Git-it
①安装nodeJS
②npm install git-it -g
③打通关
④理解并记忆每关的命令
