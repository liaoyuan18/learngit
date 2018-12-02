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

加一行，测试

git checkout -b dev     创建一个叫dev的分支，并把它设置为HEAD,等同于下面两行代码
=>  git branch dev
    git checkout dev


git checkout master     切换到master分支
git merge dev           合并master到dev

关于分支的操作

Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>




创建了feature分支
