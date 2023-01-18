

## git 사용법

1. git init
## 로컬PC의 작업 경로를 git 저장소로 등록

2. git add 파일명 or git add .
## 로컬 git 인덱스에 (파일명) 파일 추가 or 저장소의 전체 파일에 대해 인덱스 업데이트 (add .)

3. git commit -m "로그명"
## 로컬에 (로그명)으로 git commit 

4. Branch 생성하기

	ㅇ git branch 브랜치명 / git checkout 브랜치명
	## 브랜치명의 브랜치 생성 --> 브랜치로 이동 (check)

	or 

	ㅇ git checkout -b 브랜치명
	## (브랜치명)의 브랜치 생성 후, 브랜치로 이동

5. git branch
## 로컬 저장소의 브랜치 현황(list) 조회

6. git merge 브랜치명
## 현재 체크아웃된 브랜치(일반적으로 main)에서 (브랜치명)의 브랜치를 병합
## Ex. git merge dev (main 브랜치에 dev 브랜치의 변경된 내용을 병합)

7. git status 
## 로컬 저장소 및 인덱스의 git 상태 조회 (업데이트된 파일, 신규 파일 등 체크)

8. git log
## 로컬의 git log 조회 (commit 이력 등)

9 git remote add origin URL
## 중앙 github 저장소(origin)에 연결 

10. git remote -v / git ls-remote
## github 연결 상태 조회

11. git push origin master
## 중앙 github 저장소로 업로드

12. git pull

13. git clone

14. git fetch


