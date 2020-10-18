# Git版本管理

查看状态
```
git status
```

将工作区文件修改添加到暂存区
```
git add <file>
```

将暂存区的所有内容提交到本地仓库
```
git commit -m '提交描述'
```

丢弃暂存区修改
```
git reset HEAD <file>
```

版本库的版本替换工作区版本
```
git checkout -- <file>
```

删除文件
```
git rm <file>
```

版本间穿梭
```
git reset --hard commit_id
```

查看提交历史
```
git log
一行展示
git log --pretty=oneline
查看分支
git log --graph
查看分支一行展示，并且只展示前几位hash值
git log --graph --pretty=oneline --abbrev-commit
```

查看历史命令
```
git reflog
```