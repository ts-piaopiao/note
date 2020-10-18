# Git分支管理

查看分支
```
git branch
```

创建分支
```
git branch <分支名字>
```

切换分支
```
git checkout <分支名字>
或者
git switch <分支名字>
```

创建并切换分支
```
git checkout -b <分支名字>
或者
git switch -c <分支名字>
```

合并分支
```
git merge <分支名>
// 加上--no-ff可以查看合并分支信息
git --no-ff merge <分支名>
```

删除分支
```
git branch -d <分支名>
```

查看分支合并图
```
git log --graph
查看分支一行展示，并且只展示前几位hash值
git log --graph --pretty=oneline --abbrev-commit
```