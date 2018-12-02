开始学习git
git init                初始化一个代码仓库
git add                 加入暂存区
git commit -m "解释"    提交
git status              查看当前文件的状态
git diff                查看文件的具体变化
git reset --HEAD^       回到当前版本的上一个版本，HEAD代表当前版本，^代表当前版本的上一个版本，可以写多个^代表往上回退多少个版本
git reset --HEAD~100    回退到100个版本之前
git reset --HEAD <版本号>   回退到版本号对应的状态
git reflog                  可以查看log中没有的版本，在log中，回退后，就看不到回退之前那个版本的情况。

git 分为工作区、版本库
