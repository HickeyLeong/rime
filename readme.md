简易的命令行入门教程:
Git 全局设置:

```
git config --global user.name "pykali"
git config --global user.email "6554986+pykali@user.noreply.gitee.com"
```
创建 git 仓库:

```
mkdir rime
cd rime
git init 
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://gitee.com/pykali/rime.git
git push -u origin "master"
```
已有仓库?
```
cd existing_git_repo
git remote add origin https://gitee.com/pykali/rime.git
git push -u origin "master"
```
