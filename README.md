# gitProject
git@github.com:inluo/gitProject.git
[branch "master"] 
	remote = origin 
	merge = refs/heads/master
[remote "origin"] 
	url = git@github.com:inluo/gitProject.git
	fetch = +refs/heads/*:refs/remotes/origin/* 
	push = refs/heads/master:refs/heads/master
