# 一、先注册一个github用户
```

https://github.com/join

```

# 二、 安装git

在命令行中分别配置用户名和邮箱

```

git config --global uesr.nam 'github用户名'
git config --global uesr.email 'github邮箱'

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
