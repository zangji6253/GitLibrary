# GitLibrary
Git图书馆

git checkout -b serverfix origin/serverfix

git svn rebase

git svn fetch

[svn-remote "svn"]

	url = svn://192.168.1.223
	
	fetch = trunk:refs/remotes/origin/trunk
	
	branches = branches/*:refs/remotes/origin/*
	
	tags = tags/*:refs/remotes/origin/tags/*
