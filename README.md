# 前置工作 打开git bash
git config --global user.name "pandanzhe"
git config --global user.email "jing.li.625@whu.edu.cn" 


# 进入代码目录
# 初始化git仓库
git init 
# 添加到暂存区
git add .
# 提交到本地仓库
git commit -m "v1:初始代码"

# 打标签
 git tag v1

# 关联远程仓库
git remote add origin https://github.com/pandanzhe/test_git.git  

# 设置主分支名
git branch -M main

# 推送代码和标签到github
git push -u origin main