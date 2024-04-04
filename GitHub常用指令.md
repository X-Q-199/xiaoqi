# GitHub常用指令

## 克隆已有项目仓库

```
git clone 你的项目地址
```

## 创建新仓库：初始化git

```
git init
```

## 设置邮箱地址和用户名

```
git config --global user.email "2218120484@qq.com"
git config --global user.name "xiaoqi"
```

## 连接远程仓库

把origin连接到远程仓库,origin指的是本地仓库，

```
git remote add origin 你要连接的仓库地址
```

## 查看状态

```
git status
```

## 添加当前项目文件到本地git仓库

```
git add .
```

'.'表示添加当前所有文件，除了.gitignore中指定的目录或文件

## 备注并提交

```
git commit -m '你的备注'
```

此时并不是添加到远程仓库，只是本地仓库

## 推送远程仓库

这一步才是把本地修改上传到远程仓库

把origin推送到master分支上：

```
git push origin master
```

设置参数-u，方便下次推送可以简化命令：

```
git push -u origin master
```

设置-u的推送后再推送的话，只需要执行命令：

```
git push
```

## 查看日志

```
git log
```

## 退出log查看

按一下Q键就好了

## 创建分支

```
git branch 你的新分支名称
```

## 更改本地分支名

```
git branch -m master main
```

## 查看分支

```
git branch
```

## 切换分支

```
git checkout 你要切换到的分支名称
```

## 新建并切换到新的分支

```
git checkout -b 你要创建的分支名称
```

## 合并分支

把分支1合并到当前分支

```
git merge branch1
```

## 删除分支

删除分支1

```
git branch -d branch1
```

## 拉取远程分支到本地

把master的内容拉取到本地origin

```
git pull origin master
```

