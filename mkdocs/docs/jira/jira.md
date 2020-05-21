# How to integrate Jira with Slack

## issue 발생 시 Slack Notification 처리 방법



### Jira 작업

* 설정->앱 을 선택한다.
![Alt text](image/1.png)

* slack 을 검색하고, 결과에서 Slack Jira Integration을 클릭한다.
![Alt text](image/2.png)

* Slack Jira Integration 설치 화면이 나타난다.
![Alt text](image/3.png)

* 설치 를 클릭한다.
![Alt text](image/4.png)

* 상단에 설치가 진행되고 있음을 팝업으로 보여준다.
![Alt text](image/5.png)

* 설치가 완료되었음을 팝업으로 보여준다.
![Alt text](image/6.png)

* Slack Integration을 선택한다.
![Alt text](image/7.png)

* Sign in with Slack을 클릭한다.
![Alt text](image/8.png)


### Slack 작업
Jira로부터 알림을 받을 워크스페이스를 생성한다.

* 이메일 입력
![Alt text](image/10.png)

* 이메일로 전달된 Confirm 코드를 입력한다.
![Alt text](image/11.png)

* 회사명 또는 팀 이름을 입력한다.
![Alt text](image/12.png)

* Workspace 이름을 지정한다.
![Alt text](image/13.png)

* 퍼미션 설정을 하고 Allow를 클릭한다.
![Alt text](image/14.png)

### Jira 작업
Slack으로 전달할 항목을 지정한다.

* Slack과 연결된 Workspace를 확인한다.
![Alt text](image/16.png)

* Project notifications 탭을 선택하고 Create를 클릭한다.
![Alt text](image/17.png)

* Slack 채널을 선택하고 채널로 전달할 때 사용할 토픽을 지정한다.
![Alt text](image/19.png)

### Slack App
* Jira작업에 따라 Slack Workspace연결과 channel이 Issue라는 토픽으로 연결 되었음이 나타난다.
![Alt text](image/20.png)

### Jira 작업
* Jira에서 이슈를 생성한다.
![Alt text](image/21.png)

### Slack App
* opsgo 채널로 정상적인 notification이 전달됨을 확인할 수 있다.
![Alt text](image/22.png)
