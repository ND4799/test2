
配置
>* git config --global user.name "username"  //全局设置用户名
>* git config user.name "username"  //局部设置用户名
>* git config --global user.email "email@.com" //全局设置邮箱
>* git config user.email "email@.com" //局部设置邮箱


或在命令行上创建一个新的存储库
>* github上的顺序是init add comm，然后branch改名会报错，因为这个时候的提交是假提交，没有名字和email，所以在init之后要马上配置名字和email，然后在add comm branch -M

>* git init     //把当前文件夹初始化成git仓库，执行命令后当前文件夹会有一个隐藏的.git文件夹，代表成功
>* git config --global user.name "username"  //全局设置用户名
>* git config user.name "username"  //局部设置用户名
>* git config --global user.email "email@.com" //全局设置邮箱
>* git config user.email "email@.com" //局部设置邮箱 
>* git add README.md  //往暂存区增加readme
>* git commit -m "first commit"  //往本地版本库提交
>* git branch -M main  //github更改了主干由master——》main，这个是改名字
>* git remote add origin https://github.com/rexzhang4799/demo.git  //关联远程仓库
>* git push -u origin main  //推送到远程仓库
...或从命令行推送现有存储库
>* git remote add origin https://github.com/rexzhang4799/demo.git
>* git branch -M main
>* git push -u origin main

撤销操作
>* git reset --hard HEAD^   //版本回退一次
>* git reset --hard 版本号   //版本回退到指定版本号
>* git reset HEAD     //版本库文件替换暂存区文件
>* git checkout HEAD x.txt  //版本库文件替换暂存区和工作区文件
>* git checkout --x.txt  //暂存区文件替换工作区文件
>* git rm --cached x.txt //暂存区删除文件

分支操作
>* git branch <name>  //新建分支hehe
>* git checkout <name>  //切换到分支hehe
>* git push origin <name>  //提交分支到远程仓库
>* git branch  //查看分支
>* git branch -a //查看所有分支
>* git branch -r //查看远程分支
>* git branch -d <name> //删除本地分支<name>
>* git merge <name> //合并某分支<name>到当前分支
>* git push origin --delete <name> //删除远程分支




如果你没有看到.git目录，那是因为这个目录默认是隐藏的，用ls -ah命令就可以看见。
Command+Shift+. 