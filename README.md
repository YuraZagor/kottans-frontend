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


## 3. Intro to HTML and CSS

	**Introduction to Responsive Design. Weeks 1-2**
	
		+ new: Some nuances on Box Model. Now I understand why so many css sheets start with * {margin: 0} , etc
		+ astonished: 'position relative' and 'position absolute' positioning. Funny names, taking into consideration that 'absolute' positions element *relative* to it's containing div.  Also, < operator defining direct child 
		+ will use: "n-th child" concept
		task_html_css_intro/week1-2hTMLcSS.PNG
![week1-2hTMLcSS](https://user-images.githubusercontent.com/109472016/183412006-e81ee180-ff98-423a-a4bb-f3a64d5f7b7e.png)

	**Learn HTML(Eng)**
	
		+ new: I just realised that I'd never touched on tables before. Also, datalist was a new concept to me
		+ astonished: why do we have this rather complex <label> -tag while we could make it just an attribute alongside with id, name, value and type for checkboxes 
 		+ will use: all forms seem very useful. Semantic HTML helps to make code easier to read/understand
		
		task_html_css_intro/codecademySemantic.PNG
![codecademySemantic](https://user-images.githubusercontent.com/109472016/183411930-0feb0e05-ffa8-43fb-afff-651977cad090.png)


	**Learn Css(Eng)**
	
		+ new: @font-face
		+ astonished: visibility and opacity rulesets, css-way to make letters uppercase or lowercase (text-transform: uppercase/lowercase )
 		+ will use: css is a must-have knowledge for a front-ender, so I guess I will be forced to use most of it. 
![codecademyCss](https://user-images.githubusercontent.com/109472016/183411877-5dbb96bb-7cf1-4088-bb64-bfba67bed6e2.png)


## 4. Responsive Web Design

	**Responsive web design basics**
	
		+ new: the idea to make minor breakpoints when necessary
		+ astonished: "Classic readability theory suggests that an ideal column should contain 70 to 80 characters per line (about 8 to 10 words in English)."
		+ will use: img { max-width: 100%; } and not simply 'width: 100%;'
![web dev](https://user-images.githubusercontent.com/109472016/183891539-317aa164-e580-493d-b14d-3820597728e2.png)

	**FLEXBOX. Вчимося верстати на флексах**
	
		+ new: you have to apoint 'order' for every element - even if U apointed 2 out of 3, U still have to directly apoint th 3rd one's order  
		+ astonished: "flex-basis" + "flex-grow" & "flex-shrink" (why to have basis if one can make it bigger or smaller?) 
 		+ will use: 'margin right: -8px;' for the left div + 'padding left: 8px;' for the right div for distancing
![flexbox](https://user-images.githubusercontent.com/109472016/183891402-f6481c6e-abdc-4f57-a544-a82bf2349104.png)


	**Flexbox Froggy**
	
		+ new: 'flex-flow' as a joint of flex-direction and flex-wrap  
		+ astonished: oreder here worked without apointing this attribute to every item in formatted div (as was mentioned in video2 of prev sub-topic)
![froggy](https://user-images.githubusercontent.com/109472016/183891458-1aced67a-ea13-4720-8228-55136dd835dc.png)

	**CSS Grid Layout**
	
		+ new: minmax(X (px/%/min-content/max-content/auto)),Y (px/fr/%/max-content/auto)) .  
		 1fr can be max in 'minmax', but cannot be min (As I get it, 1fr makes it take most space available, which contradicts with the idea of 'min') 
		+ astonished:  cases like 'minmax(max-content, auto)'  or  'minmax(50%, min-content)'
		+ will use: grid layout seems great for responsive sites
 ![CSS Grid Layout](https://user-images.githubusercontent.com/109472016/183891295-cb651e16-86c9-4c66-bec7-84f4d5f6ca52.png)
	

	**Grid Garden**

		Nothing new, good practice
		
![gridGarden](https://user-images.githubusercontent.com/109472016/183886037-40ae3039-22ae-4b4c-a10c-7201a2bb642c.png)

