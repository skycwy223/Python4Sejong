# 강의 자료 다운로드 하기

본 강의에 대한 모든 자료는 다음 [링크](https://github.com/YoonJoon/Python4Sejong)를 참조하시기 바랍니다.

## 시작하기

1. [https://github.com/YoonJoon/Python4Sejong](https://github.com/YoonJoon/Python4Sejong) 접속  
오른쪽 "Fork" 버튼 클릭

<img width="626" alt="step_1" src="https://user-images.githubusercontent.com/1378925/40343675-f7ba936a-5dcb-11e8-8a47-f66392969fce.png">

2. 내 계정 아래 복사가 되었음을 확인 후, "Clone or download" 버튼 클릭  
"Clone with HTTPS" 에 나오는 주소를 버튼을 클릭하여 복사  
(주의 : "Clone with SSH" 아님!!)  

<img width="626" alt="step_2" src="https://user-images.githubusercontent.com/1378925/40343708-2727a340-5dcc-11e8-9085-f7d2fb80517c.png">

3. 본인의 주피터 노트북 환경으로 돌아와 새로운 터미널 생성

<img width="626" alt="step_3" src="https://user-images.githubusercontent.com/1378925/40343724-3b7f86be-5dcc-11e8-93fb-f794b8570a8f.png">

4. "git clone 복사한 주소" 를 입력

<img width="626" alt="step_4" src="https://user-images.githubusercontent.com/1378925/40343970-8aa7672e-5dcd-11e8-917b-88e8013502be.png">

5. Python4Sejong 폴더가 생겼음을 확인

<img width="626" alt="step_5" src="https://user-images.githubusercontent.com/1378925/40344015-ca4d2dfa-5dcd-11e8-9613-69aacbb696e9.png">

## 새로운 내용 업데이트

매주 새로운 파일이 업데이트되었을 때, 다운로드 하는 방법

1. 본인의 주피터 노트북 환경에서 터미널 생성

<img width="626" alt="step_3" src="https://user-images.githubusercontent.com/1378925/40343724-3b7f86be-5dcc-11e8-93fb-f794b8570a8f.png">

2. 강의 자료가 올라오는 원본 레파지토리를 remote 레파지토리로 추가  
("git remote add <이름> <원본 저장소>" 명령어를 사용하여 추가)

remote 레파지토리 추가 전 화면>  

<img width="626" alt="before_update" src="https://user-images.githubusercontent.com/1378925/40348522-e79cf26c-5dde-11e8-90b4-a5ed211fbe96.PNG">

remote 레파지토리 추가 후 화면>  
("git remote -v" 명령어로 upstream이란 이름으로 제대로 추가되었음을 확인)

<img width="626" alt="add_remote" src="https://user-images.githubusercontent.com/1378925/40348526-eb249228-5dde-11e8-9916-42e0db533d12.PNG">

3. 원본 저장소로부터 최신 업데이트를 가져온다  
("git fetch <2번에서 정한 이름>" 명령어 사용)

<img width="626" alt="git_fetch" src="https://user-images.githubusercontent.com/1378925/40348907-f5e9f86e-5ddf-11e8-95c4-b69f794b7f8d.png">

4. 서로 다른 부분을 merge하는 작업을 수행한다  
("git checkout master" 명령어 사용)  
("git merge <2번에서 정한 이름>/master" 명령어 사용)

<img width="626" alt="git_merge" src="https://user-images.githubusercontent.com/1378925/40348805-a769ca98-5ddf-11e8-945e-2356f25331b5.PNG">

5. 위 과정은 로컬 주피터 환경에서 일어난 것으로 마지막으로 깃허브에도 업데이트를 해주기위해 push를 한다.  
("git push origin master" 명령어 사용)    
(GitHub의 username과 password 입력)

<img width="626" alt="git_push" src="https://user-images.githubusercontent.com/1378925/40351697-028323cc-5de8-11e8-8173-0f45e7d6748d.PNG">

