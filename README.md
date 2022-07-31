Stage 0.
========


# 0. Git Basics

 Info about git became more clear. I definetly will use big part of it, but decided for now concentrate on simpler part and touch on more advanced in due time with a reference.

## Git:
	** Udacity **
		- new: git bash (I used to use cmd terminal :) )
		- astonished: the way ~ and ^ ancestors count
		- will use: 'Always check git status'
![udacity](https://user-images.githubusercontent.com/109472016/182022492-cca335bd-8f73-4af7-aa6a-4c688803d1b3.png)

	 **learngitbranching.js.org** :
		- new: remote repo
		- astonished: push and pull arguments
		- will use: git pull --rebase


## 1. Linux CLI and Networking

	 **Linux Survival** 
		- new: cat, kill -9, > & >> operators
		- astonished: finger :)
		- will use: > & >>, cat
![linux-mod1](https://user-images.githubusercontent.com/109472016/182022550-3a495c20-f3e6-4f8d-bbcc-4f990f969d3f.png)

	 **HTTP**
		- new: almost all -  TLS / SSL, protocol workflow 
		- astonished: caching
		- will use: TLS / SSL, GET, POST 
		
		
## 2. Git Collaboration

	**Introduction to Git and GitHub. Weeks 3, 4**
	
		+ new: Now I understood how we decide if we use merge or rebase (first if we don't bother about linear
		  structure, second if we don't need 'historical order' of changes)
		+ astonished: sing # to adress issues by order- say #2 to adress issue #2, and closing it with "Closes: #2"
		  text at the end of a comment body of a commit or a pull request 
		+ will use: Always sync my brances BEFORE starting any work on my own
![mod3gitDone](https://user-images.githubusercontent.com/109472016/182022620-a92bbd12-0cc7-47c8-9aae-fa6d1f6fe74d.png)
![mod4gitDONE](https://user-images.githubusercontent.com/109472016/182022627-13067f09-b912-4c73-a0c2-f0b7d0f01e7a.png)

	**learngitbranching.js.org**
	
		+ new: here I got that I didn't have to go through the whole course in part 0. Git Basics
		+ astonished: mixing '~' & '^' in one command like git checkout HEAD~^2~3
 		+ will use: git reset HEAD^ => for local branch (erase cast commit as if there was none and move HEAD as
		  supposed to the last of remaining commits), git revert HEAD makes new commit that set the stage as it
		  was before the commit we need to revert, and suits for remote branches
![learngitbranching](https://user-images.githubusercontent.com/109472016/182022607-774eb473-7e2f-484e-9d13-05aabf79f326.png)
