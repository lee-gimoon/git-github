- git  
파일의 변경내역을 게속해서 추적하여 변경내역 관리하는 version control system.    
보통은 text파일에서 사용하지만 img, song, excel 등 모든 파일에서 쓸 수 있음. => git은 파일을 binary format으로 인식해서.   
  
- github  
파일 내역과 파일들을 올려주는 공간.  
git version 파일의 변경된 코드를 탐색할 수 있게 도와줌.


- commit  
commit은 기본적으로 파일의 버전 저장 시점(pointing time).  
즉 commit이 50개 있으면 파일의 버전이 50개 있다는 말.

- push  
깃허브 저장소에 내 코드를 저장한다는 말.  

- README 파일  
모든 저장소가 가지고 있어야되는 파일 
markdown 확장자로 만들어야됨. markdown은 서식이 있는 파일임.

- github desktop 앱을 이용하기  
commit하는 법: summary 칸에 commit 제목을 쓰고 commit to main을 누르면 됨.  
push하는 법: publish branch 누르면 됨.

- ginore
윈도우나 맥os는 파일에 보이지않는 임시파일이 있는데 git은 디렉토리의 모든 파일을 참조할 수 있어서 보이지않는 임시파일이 깃허브에 업로드됨.  
따라서 이 보이지않는 임시파일을 업로드 하지 않게 하기위해 .gitignore파일을 만들어서 임시파일을 넣으면됨.  
.gitignore 파일: 무시하고 싶은 파일 이름을 기록하는 파일.
