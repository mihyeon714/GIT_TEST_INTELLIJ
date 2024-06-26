* git 공부중 
* intellJ도 모르는데 하려니 정말 뭐가 뭔지 모르겠다
* 되돌리기 test 성고 git checkout 경로/파일 > 파일의 이전 commit 이후 작업 전체 삭제 

------------------
------------------

* branch 실습 1 

* 기본 브랜치 : master (명칭변경가능)
* feature 라는 브랜치 생성 : git branch feature
* branch 목록 확인 : git branch
* 생성한 branch(feature)로 이동 : git checkout feature

------------------
------------------

* git clone 실습1
* git clone https://github.com/[USERNAME]/[PROJECTNAME].git
* clone 중 오류 : SSL certificate problem: self-signed certificate in certificate chain
* intellj에서 오류가 생겨서 터미널 접근을 못해서 git bash 로 터미널열어서 명령어 실행 
* git config --global http.sslVerify false

------------------
------------------

*git merge 실습 
*회사에서 encoding UTF-8 로 해당 파일 수정 후 push 
*집에서 페치 및 머지 실행 
*git fetch origin feauture/1
*git merge FETCH_HEAD feauture/1
*merge 작업중 충돌 오류 발생 > 충돌해결하기 파일갔더니 비교해줘서 걍 골라서 저장했다 
*그리고 터미널에 상태가 feauture/1|MERGING 상태길래 자세히 읽어보았더니 git commit 을 해서 merge를 종료하라는 내용이었음 
*자꾸 workspace.xml 상태가 바뀌는데 저거는 JAVA PROJECT 생성했을때 알아서 멋대로 바뀌는 그런애 같음 아직 뭔지 모르겠음 
------------------
------------------
*git merge 학습 
*git fetch 는 원격저장소의 정보를 가져와서 포인터만 형성된 상태로 아직 로컬 저장소에 반영된 상태는 아님 
*git merge 작업으로 로컬에 반영할 수 있음 
*git merge 시 충돌은 피할 수 없는 운명인 것 같기도함 
------------------
*병합 방식
*Fast-Foward 병합
*3-Way병함
