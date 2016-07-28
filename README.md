1. Spring Starter Project 생성
	
	- Name : MosaicWeb
	- Type : Gradle(Buildship)
	- Packaging : War
	- Group : com.hybrid
	- Artifact : MosaicWeb
	- Package : com.hybrid
	
	- Dependencies 선택 : web
	
2. 형상 관리

	- Remote Repository 생성 (github.com)
	- Local Repository 생성
		- >> git status
		- >> git log
		- >> dir /A .gitignore
		- >> notepad .gitignore
		- > git init
		- >> git add *
		- >> git commit -m "first commit"
	- Local ==> Remote Push (최초 동기화)
		- >> git remote -v
		- >> git remote remove origin
		- >> git remote add origin https://github.com/chlwltn0219/MosaicWeb.git
		- >> git push -u origin master