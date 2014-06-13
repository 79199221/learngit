$ mkdir learngit
$ cd learngit
$ pwd
/Users/michael/learngit

$ git init
Initialized empty Git repository in /Users/michael/learngit/.git/

$ git add readme.txt

$ git add file1.txt
$ git add file2.txt
$ git add file3.txt
$ git commit -m "add 3 files."

$ git remote add origin git@github.com:michaelliao/learngit.git

$ git push -u origin master		//就可以把本地库的所有内容推送到远程库上
$ git push origin master 		//把本地master分支的最新修改推送至GitHub
$ git clone git@github.com:michaelliao/gitskills.git	//克隆远程库

$ git checkout -b dev			//创建dev分支，然后切换到dev分支

$ git branch dev				//创建dev分支
$ git checkout dev				//切换到dev分支
$ git branch					//查看当前分支












