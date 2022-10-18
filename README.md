# Portpolio : 드론 프로젝트

## 주요기능
### Android개발 부분과 php통신 부분 담당
#### 1. Android Studio와 Dronekit API를 활용해 드론 조종 App을 만들고 드론과 연결하면 원하는 구역을 드론이 자율주행 할 수 있음
- 드론의 위치 지도에 실시간으로 표시
- 드론의 이륙고도와 속도, 비행모드 등을 조종 할 수 있음

![드론앱지도표시](https://user-images.githubusercontent.com/49406539/177550508-4d76f5f0-7113-409a-a3a6-798485b7421b.jpg)





#### 2. 드론에 개발용 보드인 TX2와 웹캠을 장착하여 드론이 자율주행 하는동안 실시간으로 드론App에서 검출된 쓰레기 개수와 종류 확인 가능
- Darknet과 YOLO를 활용한 학습을 바탕으로 쓰레기 종류를 구분해 데이터로 저장
- socket 통신을 통해 쓰레기 데이터를 실시간으로 APP에 받아와 확인할 수 있음

![image](https://user-images.githubusercontent.com/49406539/177550767-db337adf-21b7-41be-a0b8-3f77cdb5822e.png)
