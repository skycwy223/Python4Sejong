# 프로그래밍 숙제 업로드하기

숙제를 진행하시기 전에 반드시
[강의 자료 다운로드 하기](https://github.com/YoonJoon/Python4Sejong/blob/master/howToDownloadCourseMaterials.md)를 통해 
본인의 레파지토리를 최신 상태로 업데이트해주세요.

본 문서는 위 과정을 통해 최신 파일을 다운받았다는 가정 하에 숙제를 풀어 수정된 파일을 본인의 깃허브에 업로드하는 방법에 대한 내용입니다.

## 숙제하기

1. 먼저 주피터 노트북에서 숙제할 파일을 엽니다.  
여기에선 activity_0.ipynb을 예제로 설명하겠습니다.

<img width="626" alt="before" src="https://user-images.githubusercontent.com/1378925/40573578-6dd00f5a-60fe-11e8-9021-c0383a32220b.png">

2. 숙제의 목표는 activity_0.ipynb 파일에서 "This is for the homework"이라는 문자를 print 하는 것입니다.  
그러면 아래 그림과 같이 숙제를 열심히 풀고 결과를 확인해봅니다.  

<img width="626" alt="after" src="https://user-images.githubusercontent.com/1378925/40573608-ca10c0c0-60fe-11e8-9639-67b7d224b1bf.png">

3. "This is for the homework"이라는 문자가 제대로 print됨을 확인합니다.  

## 자신의 GitHub에 제출하기

이제 주피터 노트북에서 수정한 activity_0.ipynb 파일을 본인의 GitHub 레파지토리로 업로드 하는 방법입니다.

1. git add .  
변경된 파일을 추가하는 명령어입니다.  
git add activity_0.ipynb 와 같이 파일 이름을 직접 명시해도 되며, 바뀐 파일을 모두 추가하고자 할때는 파일명 대신 .을 입력합니다.

2. git commit -m "메세지"  
파일을 업로드할때 추가할 메세지를 입력합니다.  
가급적 영어로 작성해주세요.(예> Complete HW#1 )

3. git push origin master  
3번 명령어 입력 후에 자신의 GitHub username과 password를 입력하시면 파일이 업로드됩니다.  
(첫번째로 입력하는 username은 메일주소가 아닌 아이디를 입력하셔야 합니다.)

<img width="626" alt="after" src="https://user-images.githubusercontent.com/1378925/40573646-5cc46ef8-60ff-11e8-889d-6cc0e0939f66.png">
