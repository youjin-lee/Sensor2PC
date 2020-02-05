# Sensor2PC

## :cactus: Method of Connection

### 1. role of PC = Host(AP), role of SENSOR = Client
<div>
  <br> </br>
  <img width="600" src = "https://user-images.githubusercontent.com/27392019/73799699-033dcf80-47fa-11ea-8e26-373eef145c5e.png">
 </div>
 
 - PC가 서버(Host)가 되고, Sensor가 클라이언트가 되는 경우
 
 - **WiFi** : Sensor에서 Port number, AP 정보를 PC에 전달
 
 - **BLE** :



<div>
  <br> </br>
  <img width="600" src = "https://user-images.githubusercontent.com/27392019/73799696-ffaa4880-47f9-11ea-8da0-8abf71765644.png">
 </div>

1. AP모드에서, 회로-회로 연결
2. excel 파일 문서, TCP서버에서 기기랑 연결할때
3. TCP서버를 만들어서 모듈을 만들고, 기존의 있는 함수를 베이스로, 계정관련, 기기등록 제외하고 (Socket 통신하는 동안에만 하도록)
5. 의자(host)가 AP모드에서 물리도록, pc - client
6. 구현은 의자가 host인 것이 더 간단함. 단점은 인터넷 연결. 서버로 측정하면서 바로 업로드. 연결 어플리케이션, 수집 어플리케이션 따로 필요.

=> PC가 AP일때, 또는 의자가 PC한테 정보를 보내줌
=> (python) twisted - tcp 경량화 프레임워크. 
colab.research.google.com/drive/1xNL2mKBvvpMRcw5_OU7RbD-xKz1CG_95

ap : access point 공유기 정보
ui와 tcp 서버 연결 (process과 다를것이므로)

flask, tcp 통신

시계열 데이터 수집
