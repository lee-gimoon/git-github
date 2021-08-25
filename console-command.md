- git log  
커밋한 history를 볼 수 있음.  
histoty창 끄는법 => q 입력

- git add .  
현재 폴더의 모든 파일을 stage-area에 올려놓기.

- git commit -m "message"  
stage-area에 있는 파일을 커밋 메세지와 함께 커밋하기.

- git push origin main  
커밋한 파일을 푸시하는 명령어.  
origin: 원격저장소(github-repository), main: push하고 싶은 branch

- 용어 HEAD  
마지막 커밋을 가리키는 포인터. => 즉, 현재 브랜치의 마지막 커밋을 가리킴.

- git checkout 과거 커밋  
과거의 커밋으로 돌아가게 하는 코드.  

- git checkout master  
다시 현재상태로 돌아오게 하는 코드.

- git reset --hard HEAD^  
이전 커밋으로 돌아가게 하는 코드. 단, 돌아가는 커밋보다 미래 커밋을 삭제하고 돌아감.  
--hard: 삭제한다는 뜻.  
HEAD^: 현재 HEAD위치에 한 커밋전으로 돌아감. ^^쓰면 두 커밋전으로 돌아감.

- git push origin main --force  
강제로 푸시.




























