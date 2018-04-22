# 一、先注册一个github用户
```

https://github.com/join

```

# 二、 安装git

在命令行中分别配置用户名和邮箱

```

git config --global user.nam 'github用户名'
git config --global user.email 'github邮箱'

```

# 三、初始化仓库
先在任意目录右键打开'git-bash'

```

mkdir git   新建一个空的目录        
cd git      进入这个目录
git init    初始化一个git仓库

```
# 工作流程

```
touch 1.txt 创建一个文件
git add 1.txt 添加暂存区
git commit -m 'add' 把文件添加历史区 
git log  查看历史纪录

```
#增加删除文件

```
#添加指定文件到缓存区
git add [file1] [file2]...

#添加指定目录到缓存区，包括子目录
git add [dir]

#添加当前目录的所有文件到暂存区
git add .

#添加每个变化前，都会要求确认
#对于一个文件的多处修改，可以实现分次提交
git add -p

#删除工作区文件，并且将这次删除放入暂存区
git rm [file1] [file2] ...

#停止追踪指定文件，但该文件会保留在工作区
git rm --cached [file]

#改名文件，并且将这个改名放入暂存区
git mv [file-original] [file-renamed]

```
#代码提交

