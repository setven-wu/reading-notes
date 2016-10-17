# Git

git 学习笔记

## 常见问题

当我们提交了一个 pull request 时，对方没有及时接受，而我们又提交了其他的文件，此时这些所有的提交都将与之前的那个 pull request 一起提交过去。

有时我们并不希望多个开发任务一起提交，而是每个开发任务实现后单独提交一个 pull request。此时，你可以选择使用分支，每一个分支对应一个开发任务，你可以这样做：

## 常见操作

```shell
# 查看当前所有分支
git branch

# 切换分支
git checkout <branch_name> 

# 新建音乐模块开发任务所对应的分支并进行工作
git checkout -b music

...写代码 ...

git add .
git commit -m "add some files"
git push origin music

# 把 music 分支提交为一个 pull request

# 把分支合并到 master 并删除分支
git checkout master
git merge music
git branch -d music
git push origin --delete music

# 新建文件模块开发任务所对应的分支
git checkout -b file
....
```

### 取消 add

当我们使用 `git add some files` 往缓存区添加了文件后，我们希望取消添加，可以使用命令：

```shell
# 取消缓存，如果不指定文件，则取消所有文件的缓存
git reset HEAD <file>...
```

### 如何取消 commit 
	
当我们使用 `git commit -m "add some files"` 往版本库中添加了一个提交，我们想取消这次提交，可以使用命令：

```shell
# 回滚到指定的提交版本
git reset <commit_id> 
```

如果你已经在 `commit` 后，通过命令 `git push origin master` 把版本库同步到了远程服务器，那么你希望远程服务器回滚到该历史，你可以执行 `reset` 操作后，再执行：

```shell
# 强制把远程服务器于本地版本库保持一致
git push origin master --force
```

此时，远程服务器就会回滚到 `reset` 后的版本了。

#