### github项目quick setup
![](https://images2018.cnblogs.com/blog/596306/201805/596306-20180504144307905-1584657010.png)
### git初始化
    git init

### git添加remote
    git remote add origin YOURS_REMOTE_URL

### git修改remote的url
    git remote set-url origin YOURS_NEW_REMOTE_URL

### git设置push时当前branch对应的remote
    git push --set-upstream origin master

### 查看远程和本地的所有分支
    git branch -a

### 本地新增分支a
    git checkout -b a

### 对应的远程新增分支a
    git push <REMOTE-BRANCH <LOCAL-BRANCH:<REMOTE-BRANCH-ADD
    git push origin a:a

### 删除远程分支
    git push origin :a

### 使当前local分支追踪remote的某一分支
    git branch --set-upstream-to=<remote/<branch local-branch
    git branch --set-upstream-to=origin/asset-manage asset-manage
