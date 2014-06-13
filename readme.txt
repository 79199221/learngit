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