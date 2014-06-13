$ mkdir learngit				//创建一个空目录
$ cd learngit					//切换目录
$ pwd							//显示当前目录

$ git init						//把这个目录变成Git可以管理的仓库

$ git add readme.txt			//文件添加到仓库

$ git commit -m "add 3 files."	//把文件提交到仓库

$ git status					//仓库当前的状态
$ git diff readme.txt 			//查看修改内容
$ git log						//git log命令显示从最近到最远的提交日志
$ git log --pretty=oneline		//
$ git reset --hard HEAD^		//回退到上一个版本
$ git reflog					//查看命令历史，以便确定要回到未来的哪个版本。

$ git remote add origin git@github.com:michaelliao/learngit.git

$ git push -u origin master		//就可以把本地库的所有内容推送到远程库上
$ git push origin master 		//把本地master分支的最新修改推送至GitHub
$ git clone git@github.com:michaelliao/gitskills.git	//克隆远程库

$ git checkout -b dev			//创建dev分支，然后切换到dev分支

$ git branch dev				//创建dev分支
$ git checkout dev				//切换到dev分支
$ git branch					//查看当前分支
$ git merge dev					//合并指定分支到当前分支
$ git branch -d dev				//删除dev分支

$ git log --graph --pretty=oneline --abbrev-commit	//分支的合并情况










