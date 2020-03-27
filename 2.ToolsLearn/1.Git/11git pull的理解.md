# 11git pull的理解


## git pull 远程库对本地库和工作区暂存区的影响
```
没有 add 的文件，不会被覆盖。
add 了文件没有 commit，不能 pull。
commit 了之后 pull 有冲突，会自行解决或者提示需要编辑。
只要 commit 过，都可以用 git reflog 找回。
```


  

## 一些git pull之后需要的命令

git diff commit id 查看具体提交id的文件变更内容


git log -p -1 查看最近1次的文件变更 -2 就是倒数第二次的


