# playwright_samples
playwright samples
```shell
# 修改本地分支名
git branch -m master <BRANCH>
# 创建远程 main 并绑定
git push -u origin main

git branch -u origin/<BRANCH> <BRANCH>
git remote set-head origin -a
# 删除远程 master
git push origin --delete master
# 拉取远程最新分支列表
git fetch --prune

# 若多人协作项目,提醒团队成员执行：
git fetch origin
git checkout main
git branch -u origin/main
git remote prune origin
```