# git bash 연습하기...

1. **git init** -> local 폴더에 .git/ 폴더를 만들어준다.  
2. **git remote add origin (reop address)** -> 프로젝트를 저장할 원격 저장소를 설정한다. origin은 원격저장소의 별칭! git remote rename으로 바꿀 수 있다.  
3. **git branch -M main** -> 브랜치 이름 바꾸기. git은 master가 default고 github는 main이 default다.  
3. **git add .** -> git add 다음에 인자로 준 파일들을 스테이지에 올린다.(git add . 은 모든 파일을 스테이징한다는 뜻)  
4. **git status** -> staged된 파일  리스트 출력
5. **git commit -m "first commit"** -> 히스토리 만들기! 커밋 생성  
6. **git remote -v** -> 스테이징된 파일들이 올라갈 원격 저장소 확인!
7. **git push origin master** -> origin(원격저장소)의 master브랜치로 푸쉬한다.  
