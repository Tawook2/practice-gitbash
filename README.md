# practice-gitbash
> gitbash를 사용하는 법 및 명령어 정리본 자세한 내용은 스크린샷을 첨부하여 블로그에 게시할 예정

## git config 설정 명령어
* git config --list : 전체 config 리스트를 보는 명령어

* git config --global user.name "자신의 'git' 아이디" : 아이디 설정

* git config --global user.email "자신의 'git' 이메일" : 이메일 설정

* git config --unset user.name : 설정된 사용자 아이디 지우기

* git config --unset user.email : 설정된 사용자 이메일 지우기

* git config --unset --global user.name : 글로벌로 설정된 config 사용자 아이디 지우기

* git config --unset --global user.email : 글로벌로 설정된 config 사용자 이메일 지우기

## git 기초 명령어
* git init : 'git' 초기화 설정

* git add 파일명 -ex (git add index.html) : 파일 추가하기

* git add . : 파일 전체 추가하기

* git status : 파일 상태보기

* git commit -m "남길 커멘트" : 짧은 comment와 함께 커밋하기

* git remote add origin https://github.com/자신의 'git' 아이디/자신의 'repository(저장소)'이름.git -ex https://github.com/Tawook2/practice-gitbash.git

* git push : 커밋한 내용 git에 푸시하기

* git pull : git 내용 불러와 업데이트 하기

* git clone https://github.com/자신의 'git' 아이디/자신의 'repository(저장소)'이름.git -ex https://github.com/Tawook2/practice-gitbash.git

## Branch 관리 명령어

* git branch : 현재 관리되고 있는 branch 들을 리스트 형식으로 보여줌

* git checkout -b test origin/master : remote된 master 브랜치를 기반으로 test 브랜치를 생성과 동시에 checkout

* git checkout -b test2 : 현재 위치해있는 브랜치를 기반으로 test2 브랜치를 생성과 동시에 checkout

* git branch test3 : 현재 위치해있는 브랜치를 기반으로 checkout 이동없이 test3 브랜치 생성

* git branch -d test3 : test3 브랜치를 삭제

* git branch -D test3 : test3 브랜치를 강제 삭제 (d를 대문자 D로 변경)

## 그 외 명령어
* ls : 해당 위치에 종속된 하위 폴더 리스트 보기

* cd : 위치 이동

* cd /c : c:drive로 이동

* cd /d : d:drive로 이동

* tip : 터미널 명령어 나 파일명의 앞글자를 입력 후 'Tab' 키를 누르면 자동완성이 된다



