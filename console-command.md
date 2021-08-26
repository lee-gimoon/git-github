- git log  
커밋한 history를 볼 수 있음.  
histoty창 끄는법 => q 입력

- git status  
파일상태 내역. (? area)

- git add .  
현재 폴더의 모든 파일을 stage-area에 올려놓기.

- git commit -m "message"  
stage-area에 있는 파일을 커밋 메세지와 함께 커밋하기.

- git push origin main  
커밋한 파일을 푸시하는 명령어.  
origin: 원격저장소(github-repository), main: push하고 싶은 branch

- 용어 HEAD  
마지막 커밋을 가리키는 포인터. => 즉, 현재 브랜치의 마지막 커밋을 가리킴.

- git checkout 커밋별명  
해당 커밋으로 돌아가게 하는 코드.  

- git checkout main  
다시 현재상태(main branch)로 돌아오게 하는 코드.

- git reset HEAD^ (복합리셋)  
커밋만 삭제하고 파일 변경 사항은 그대로 둔다.  
변경 사항들을 unstage 영역에 둔다.  

- git reset --hard HEAD^ (하드리셋)
이전 커밋으로 돌아가게 하는 코드. 단, 돌아가는 커밋보다 미래 커밋, 파일변경 내역을 삭제하고 돌아감.  
--hard: 삭제한다는 뜻.  
HEAD^: 현재 HEAD위치에 한 커밋전으로 돌아감. ^^쓰면 두 커밋전으로 돌아감.

- git reset --softl HEAD^ (소프트리셋)

- git push origin main --force  
강제로 푸시.

- git git checkout -b 브랜치명  
새로운 브랜치 만드는 명령어.

- git branch  
브랜치 목록 보는 명령어.

- git branch -d 브랜치이름  
브랜치 삭제하는 명령어.

- git commit --amend -m "message"  
마지막 커밋을 새로운 메세지와 함께 수정.  
git commit --amend --no-edit: 메세지는 수정x

- git rm -r 파일이름/ --cached  
-r은 폴더 제거 할때만 추가.


















