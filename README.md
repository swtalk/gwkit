copyright @handraker
https://github.com/handraker/new-gwit

### 기능추가
* sso 로그인 기능추가
* 서버리스트 Fetch 기능 추가

### 사용법
* 기존 실행파일에 init argument 입력
  - python gwkit.py init
- sso login


![image](https://user-images.githubusercontent.com/11779505/147825295-6351063b-f90b-4547-ae26-745b15364e60.png)

### 주의사항
* Tips 의 나의서버그룹 정보를 가져와서 json 에 맵핑합니다. 
  * 호스트명 : Host
  * 서버그룹명 : Description
  * 태그 : Tags

* 한글이 존재할 경우 인코딩 이슈가 발생합니다. 
  * 로직내 검색기능은 리눅스 환경에서 한글은 추천하지 않습니다. 만약 Tips 상에 한글이 존재한다면, 영문으로 변경 후 init 부탁드립니다. 

![image](https://user-images.githubusercontent.com/11779505/148932441-267c1f5d-fbbc-401b-83d0-9b1673df500b.png)

### init 후 자동으로 등록됩니다. 
![image](https://user-images.githubusercontent.com/11779505/148932547-9d80ecdd-e0cd-476c-b970-66bcc30be99e.png)







