- git  
파일의 변경내역을 게속해서 추적하여 변경내역 관리하는 version control system.    
보통은 text파일에서 사용하지만 img, song, excel 등 모든 파일에서 쓸 수 있음. => git은 파일을 binary format으로 인식해서.   
  
- github  
깃 파일 내역과 깃 파일들을 올려주는 공간.  
git version 파일의 변경된 코드를 탐색할 수 있게 도와줌.

- repository  
깃이 보고 있는 파일의 폴더(파일). 즉, 이 폴더에 있는 모든 파일을 깃이 읽을 수 있다.

- .git 폴더  
git command, history등의 저장되 있음. 이 파일(폴더)가 없으면 git은 더이상 우리의 파일을 추적하지 않음.

- git area  
git은 3개의 area를 가지고 있음. working-area, staging-area, repository-area  
우리의 파일은 3가지중 1개의 area상태.  

- commit  
commit은 기본적으로 파일의 버전 저장 시점(pointing time).  
즉 commit이 50개 있으면 파일의 버전이 50개 있다는 말.

- branch  
main의 마지막 commit에서부터의 다른 타임라인. 즉, 독자적인 개발 라인 구축.  
Ex) 현재 지점에서 2가지 길을 만들어 각 길의 버젼을 커밋해서 마지막에 합침.  

- push  
깃허브 저장소에 내 코드를 저장한다는 말.  

- README 파일  
모든 저장소가 가지고 있어야되는 파일 
markdown 확장자로 만들어야됨. markdown은 서식이 있는 파일임.

- fork  
repository의 전체를 내 깃헙계정으로 복사한다는 말.

- clone  
깃허브에 있는 repository를 내 컴퓨터에 복사한다는 말.  
깃허브 데스크탑app 에서 add를 눌러서 원하는 저장소를 복사해오면 됨.

- github desktop 앱을 이용하기  
commit하는 법: summary 칸에 commit 제목을 쓰고 commit to main을 누르면 됨.  
push하는 법: publish branch 누르면 됨.  
update from default branch: 기본 브랜치(main-branch)의 버전의 변경사항을 해당 브랜치에 적용시킴.  
merge into current branch: 현재 브랜치에 다른 브랜치 버젼을 합침.

- gitignore 쓰임세  
윈도우나 맥os는 파일에 보이지않는 임시파일이 있는데 git은 디렉토리의 모든 파일을 참조할 수 있어서 보이지않는 임시파일이 깃허브에 업로드됨.  
따라서 이 보이지않는 임시파일을 업로드 하지 않게 하기위해 .gitignore파일을 만들어서 임시파일을 넣으면됨.  
.gitignore 파일: 무시하고 싶은 파일 이름을 기록하는 파일.

- github에서 브랜치를 가지면 좋은 이점.  
만약 특별한 이름이 붙혀진 특별한 branch를 가지고 있으면 깃허브에서 공짜로 static웹사이트를 호스팅 할 수 있도록 해준다. => branch 이름은 gh-pages로 해야됨.  
즉, 누구나 무료로 웹사이트를 업로드 할 수 있고 업로드하면 무료의 URL을 받을 수 있음.  
static웹사이트: html,css,javascript로만 이루어진 웹사이트
