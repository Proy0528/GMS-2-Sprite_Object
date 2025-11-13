---
#### 안녕하세요, 이로현입니다.
##### 언더테일 팬게임을 만들고 싶다는 바램을 이루기 위해 게임메이커 독학을 시작해보려고 합니다.
##### 유니티 vs 게임메이커 뭐부터 먼저 해볼지 고민했는데,, 결국 게임 메이커부터 찍먹(?)하고 유니티도 하려고 합니다.
##### 기초 지식과 알아두면 좋은 단축키 등등 메모하겠습니다.
##### 그리고 앞으로 게임메이커는 겜스로 줄여 부르겠습니다.
---
## 겜스 기초 지식
##### 겜스 네이버카페 : https://cafe.naver.com/crazygm
##### 겜스 카톡 단톡방 : https://open.kakao.com/o/gqC4cnx
##### 겜스 도움말 : https://manual.gamemaker.io/monthly/en/#t=Content.htm
##### 도트캣님 블로그 : https://blog.naver.com/dot_cat
##### 최적화된 tml 언더테일 엔진 : https://github.com/Panthervention/Undertale-Engine-Cheetos
---
### 알아두면 효율적인 단축키
##### ctrl + (n)번 창으로 이동 -  작업 창에 ctrl + shift + (n) [n=1~9]
##### 작업창 전부 닫기  -  오른쪽 클릭 --> windows --> 모두닫기
##### ctrl + e : 프로젝트 파일 저장 (YYP 파일 1개 파일로 저장됨)
##### ctrl + shift + f -> 검색 및 바꾸기 : 코딩한 단어 찾기 / 변경
##### 레이아웃 : 인터페이스 설정 저장 및 불러오기
---
### 게임 메이커 창
##### ctrl + n : 새 프로젝트 (new)
<img width="200" height="48" alt="화면 캡처 2025-10-26 162234" src="https://github.com/user-attachments/assets/599bbd8f-6582-4184-9245-585feb0b96ae" />

##### ctrl + o : 불러오기 (open)
<img width="200" height="48" alt="화면 캡처 2" src="https://github.com/user-attachments/assets/806ac6c1-de52-4fe5-b1a4-46ef93588dc8" />

##### ctrl + s : 저장하기 (save) 
<img width="200" height="48" alt="화면 캡처 3" src="https://github.com/user-attachments/assets/b04716ce-1d69-4388-a76a-a71ae8a5f8ec" />


##### ctrl + f8 : 실행 파일 만들기 (게임을 독립된 파일로)
<img width="200" height="48" alt="image" src="https://github.com/user-attachments/assets/4ca93557-07a3-4220-b07f-0df2044e2c17" />

##### 선택 전에 먼저 뽑을 플랫폼 선택 (배포할때 window zip 파일로 하면 될듯?)
##### <img width="500" height="543" alt="image" src="https://github.com/user-attachments/assets/113f515b-d38d-487c-b3ab-edadc1d7c9da" />
---
### 되게 중요한거
##### 순서대로 디버그(f6), 실행(f5), 정지버튼, 컴파일러 캐시 삭제
##### <img width="261" height="69" alt="image" src="https://github.com/user-attachments/assets/46622006-375e-451b-8166-1c94dacaff23" />
##### 컴파일러 캐시는 실행(f5) 할때 남아도는 캐시가 에러를 만들 수 있으므로 주기적으로 눌러서 캐시를 지워주자
##### 게임옵션(실행파일 만들때 파일 특징), 도움말
##### <img width="109" height="57" alt="image" src="https://github.com/user-attachments/assets/7664ca3c-2b02-4cc0-afaa-56368f98f79c" />
##### 게임 옵션에서 아이콘 바꾸기, 게임 이름, 저장장소 등 설정 가능
##### 그리고 도움말 많이 보는 습관 기르기!
--- 
### 겜스 기본 구조
#### 스프라이트 -> 오브젝트 -> 룸
##### 스프라이트는 순수 그림
##### 오브젝트는 수치연산과 출력
##### 룸은 스프라이트와 오브젝트의 무대
