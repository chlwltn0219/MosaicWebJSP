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
		
	- 개발자 2가 Clone 수행
		- >> git clone https://github.com/chlwltn0219/MosaicWeb.git
		- >> git clone https://github.com/chlwltn0219/MosaicWeb.git MoasicWebDev
		- Eclipse Gradle Import
		
3. HTML 설정

	- 설정 불필요
	- >> mkdir src/main/webapp 폴더 생성
	- >> notepad src/main/Hello.html
	- >> gradle bootrun
	- Firefox ==> http://localhost:8080/Hello.html	
		
4. JSP 설정

	- mvnrepository.com >> search : tomcat embed jasper
	- build.gradle dependency : 
		compile group: 'org.apache.tomcat.embed', name: 'tomcat-embed-jasper', version: '8.5.4'
	- notepad src/main/webapp/Hello.jsp
	- >> gradle bootRun
	- Firefox ==> http://localhost:8080/Hello.jsp

	