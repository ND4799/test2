
```
                   _ooOoo_
                  o8888888o
                  88" . "88
                  (| -_- |)
                  O\  =  /O
               ____/`---'\____
             .'  \\|     |//  `.
            /  \\|||  :  |||//  \
           /  _||||| -:- |||||-  \
           |   | \\\  -  /// |   |
           | \_|  ''\---/''  |   |
           \  .-\__  `-`  ___/-. /
         ___`. .'  /--.--\  `. . __
      ."" '<  `.___\_<|>_/___.'  >'"".
     | | :  `- \`.;`\ _ /`;.`/ - ` : | |
     \  \ `-.   \_ __\ /__ _/   .-` /  /
======`-.____`-.___\_____/___.-`____.-'======
                   `=---='
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
         		佛祖保佑       永无BUG


git 常用操作

配置
>* git config --global user.name "rexzhang4799"
>* git config --global user.email "57111563@.qq.com"
>* git remote add origin https://github.com/rexzhang4799/git_test.git


删除一个文件操作
>* git rm xxx.html
>* git commit -m "del xxx.html"
>* git push origin master

添加or修改一个文件操作
>* git add xxx.html
>* git commit -m "edit xxx.html"
>* git push origin master

提交操作
>* git status  \\查看修改情况
>* git add -u  \\提交修改到暂存区
>* git commit -m "信息"   \\提交到本地仓库
>* git push  \\提交到远程仓库

撤销操作
>* git checkout -- file   \\删除or修改，没有add到暂存区
>* git reset --hard HEAD   \\删除or修改，add到暂存区（也可以用下面的两个命令操作）
>* git reset HEAD  file & git checkout -- file

分支操作
>* git branch <name>  \\新建分支hehe
>* git checkout <name>  \\切换到分支hehe
>* git push origin <name>  \\提交分支到远程仓库
>* git branch  \\查看分支
>* git branch -r \\查看远程分支
>* git branch -D <name> \\删除分支<name>
>* git merge <name> \\合并某分支<name>到当前分支
>* git branch push origin --delete <name> \\删除远程分支

```