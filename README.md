# git 연결 순서

레포지토리 생성 -> 레포지토리와 같은 파일 로컬에 생성

# 1.Git config 리셋(처음 설치를 하는 경우에는 생략가능)
기존에 config파일 세팅이 되어있는경우 초기화 시키기
윈도우에서 윈도우키+R cmd창 띄우기

-----------------------------------------------

git config --system --unset credential.helper
git config --global --unset credential.helper

-----------------------------------------------

# 2.git계정 정보 입력

(저장소에서 사용하는 이메일을 적어도됨

-----------------------------------------------

git config user.email "이메일"
git config user.name "Tom"

-----------------------------------------------


# 3.프로젝트 폴더에 git 설정 (.gitignore 파일 설정)

git init을 하기전 .gitignore 파일 생성해 관리하지 않을 파일이나 폴더를 미리 설정 할 수 있게 함

.gitignore 파일 생성 (편집기에서 아래 내용을 입력하고 .gitignore 파일이름으로 저장 후 프로젝트 폴더에 위치)

-------------------------------------------------------------

# Compiled source #

###################

*.com

*.class

*.dll

*.exe

*.o

*.so

 

# Packages #

############

# it's better to unpack these files and commit the raw source

# git has its own built in compression methods

*.7z

*.dmg

*.gz

*.iso

*.jar

*.rar

*.tar

*.zip

 

# Logs and databases #

######################

*.log

*.sql

*.sqlite

 

# OS generated files #

######################

.DS_Store*

ehthumbs.db

Icon?

Thumbs.db

---------------------------------------------------------

4.Git 사용 

레포지토리 생성 후 나오는 이부분을 
해당 작업폴더의 cmd창에서 순서대로 입력해준다.

…or create a new repository on the command line
---------------------------------------------------------

git init
git add README.md //커밋 할 파일
git commit -m "커밋 할 내용"
git remote add origin https://github.com/95kds/sdfsdf.git
git push -u origin master

----------------------------------------------------------


 