_**`git相关的问题总结`**_


**远程仓库新建项目**

echo "# java-practice" >> README.md
git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/iterxywei/java-practice.git

git push -u origin master

**本地项目关联远程仓库**

git remote add origin https://github.com/iterxywei/java-practice.git

git push -u origin master

**git log 一行显示提交信息**

git log  --pretty=oneline

**git reset 回退提交**

A->B->C
当前commit版本是C，想要回退到B

git  reset  --hard  HEAD^   回退到上一个版本的commit

git  reset  --hard  HEAD^^  回退到上上版本

git reset --hard commit_id

git  reflog  查看所有的变更记录






