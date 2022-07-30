Stage 0.
============================================================================================

## 0. Git Basics

 Info about git became more clear. I definetly will use big part of it, but decided for now concentrate on simpler part and touch on more advanced in due time with a reference.

## Git:
	 Udacity
		- new: git bash (I used to use cmd terminal :) )
		- astonished: the way ~ and ^ ancestors count
		- will use: 'Always check git status'
		![udacity](https://user-images.githubusercontent.com/109472016/181925278-6c5d8122-2b5c-4a72-95f4-15c6577d163a.png)

	 learngitbranching.js.org :
		- new: remote repo
		- astonished: push and pull arguments
		- will use: git pull --rebase


## 1. Linux CLI and Networking

	 Linux Survival 
		- new: cat, kill -9, > & >> operators
		- astonished: finger :)
		- will use: > & >>, cat

	 HTTP
		- new: almost all -  TLS / SSL, protocol workflow 
		- astonished: caching
		- will use: TLS / SSL, GET, POST 
		
		
## 2. Git Collaboration

	Introduction to Git and GitHub. Weeks 3, 4
	
		- new: Now I understood how we decide if we use merge or rebase (first if we don't bother about linear
		  structure, second if we don't need 'historical order' of changes)
		- astonished: sing # to adress issues by order- say #2 to adress issue #2, and closing it with "Closes: #2"
		  text at the end of a comment body of a commit or a pull request 
		- will use: Always sync my brances BEFORE starting any work on my own

	learngitbranching.js.org
	
		- new: here I got that I didn't have to go through the whole course in part 0. Git Basics
		- astonished: mixing '~' & '^' in one command like git checkout HEAD~^2~3
 		- will use: git reset HEAD^ => for local branch (erase cast commit as if there was none and move HEAD as supposed to the last of remaining commits),
		  git revert HEAD makes new commit that set the stage as it was before the commit we need to revert, and suits for remote branches
