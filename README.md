# Sensor2PC

## :cactus: Method of Connection

### 1. role of PC = Host(AP), role of SENSOR = Client
<div>
  <br> </br>
  <img width="600" src = "https://user-images.githubusercontent.com/27392019/73799699-033dcf80-47fa-11ea-8e26-373eef145c5e.png">
 </div>
 
 - PC가 서버(Host)가 되고, Sensor가 클라이언트가 되는 경우
 
 - **WiFi** : Sensor에서 Port number 등을 PC에 전달 
 
 -> PC에서 Sensor가 접근할 수 있도록 TCP 서버 정보(AP:Access Point) 제공
 
 -> Sensor에서 PC로 연결
 
 - **BLE** :


### 2. role of PC = Client, role of SENSOR = Host(AP)
<div>
  <br> </br>
  <img width="600" src = "https://user-images.githubusercontent.com/27392019/73799696-ffaa4880-47f9-11ea-8da0-8abf71765644.png">
 </div>

 - PC가 클라이언트가 되고, Sensor가 Server(Host, AP mode) 되는 경우
 
 - **WiFi** : Sensor에서 Port number, AP 정보를 PC에 전달
 
 - **BLE** :
 
### :cherry_blossom: Decision : Method 1

<Advatage>
  - able to use internet
 
<Disadvatage>
  - more complicated than method 2.

### Tool
- (python) **twisted** : tcp 경량화 프레임워크
