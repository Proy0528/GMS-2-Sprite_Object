---
## Sprite
##### https://manual.gamemaker.io/monthly/en/#t=The_Asset_Editors%2FSprites.htm
---
### 스프라이트 창
##### asset browser에서 오른쪽 키 -> create -> create sprite
##### <img width="226" height="298" alt="image" src="https://github.com/user-attachments/assets/c8cad40e-2cb6-4698-a2bf-b324e3aa8101" />
##### 이름은 ```spr_[스프라이트 이름]``` 형식 추천함
##### edit image에서 이미지 편집
##### import에서 스프라이트 불러오기
##### size에서 인게임 스프라이트 크기 & 캔버스 크기 변경
---
##### <img width="212" height="536" alt="image" src="https://github.com/user-attachments/assets/041c9840-d68c-4700-8de2-eff8db486ddc" />
##### Tile Horizontally & Vertically는 rpg? 같은 게임에 배경 타일에 빈틈을 메꿀때 쓰이는 용도 (모바일 포트에서 많이 사용됨)
---
##### <img width="212" height="595" alt="image" src="https://github.com/user-attachments/assets/a311baaf-6ce0-46b0-9c50-b0e366863640" />
##### Collision Mask는 인게임 히트박스 설정
##### Manual (사용자 커스텀) 으로 하고 (Rotating) Rectangle로 해서 히트박스 설정 가능
##### tolerance랑 Nine Slice는 아직 몰라도 상관 없을듯
---
### 도트툴
##### edit image로 가면 도트툴이 나옴
---
##### <img width="100" height="205" alt="image" src="https://github.com/user-attachments/assets/246529cb-9707-4699-b06b-42acc5a7f7bd" />
##### 위에서부터 순서대로 - 어니언 스키닝, 반복 유형, 재생
##### 어니언 스키닝은 동작 모션 할때 좋음 (전/후 프레임이 흐릿하게 나옴)
##### 프레임 드래그 해서 순서 변경 가능
##### 프레임 위에 커서 두고 x 표시 클릭하면 삭제 가능
---
##### <img width="439" height="81" alt="image" src="https://github.com/user-attachments/assets/298db39d-f1df-48e5-a488-ef5f42585ef7" />
##### 왼쪽부터 순서대로 - 그리드, 축소, 정상화, 확대, 창에 맞춤, 화면 분할 임
##### 여기서 축소 확대 정상화 창에 맞춤은 그냥 줌인 줌아웃과 비슷함
---
### 그리드
##### <img width="405" height="366" alt="image" src="https://github.com/user-attachments/assets/1479eee9-65a6-49d1-884b-a33485fece15" />
##### 그리드는 스프라이트 위에 격자선을 그려줌 (스프라이트 간격 잴때 유용함 + 타일 배치)
##### 왼쪽부터 순서대로 - 색 설정, 격자 크기 설정, 투명률 설정(알파값), 그리고 snap 설정 가능
##### snap은 영역지정을 그리드 크기에 맞게 강제로 지정해줌

---
### 브러쉬 툴
##### 첫 이미지는 천장에, 두번째는 옆쪽에 있음
##### 브러쉬 크기, 모양, 색, 다 바꾸기 가능 (aseprite랑 비슷함,, 알아서 적을할듯?)
##### <img width="432" height="310" alt="image" src="https://github.com/user-attachments/assets/cc88b41d-d5c8-4735-b2fa-adf604128be1" />

##### <img width="327" height="208" alt="image" src="https://github.com/user-attachments/assets/9f13feaa-7780-42f3-ac4b-bdb7fa1bb98b" />
##### smooth 체크박스는 브러쉬 경계선을 부드럽게 만들어줌
##### 드래그 클릭 후 복사한 그림은 브러쉬 창에 저장됨
##### 이걸 이용해서 - 타일 스프라이트 조각 (ex : 50x50 크기) 복사 --> 그리드 + snap 사용 --> 브러쉬 창에 복사된 타일 붙여넣어 맵 만들기 가능
##### <img width="180" height="231" alt="image" src="https://github.com/user-attachments/assets/0a61c8f0-ae5e-4a97-b532-4aa81f52ec18" />
##### 우클릭 브러쉬 색이랑 좌클릭 브러쉬 색을 설정/바꾸기 가능
##### 위에 작은 팔레트는 내가 전에 썼던 색이 저장됨
---
### 툴박스
##### <img width="200" height="358" alt="image" src="https://github.com/user-attachments/assets/8acfdfab-b1b5-4c39-87c4-24ff935cf463" />
##### 브러쉬 (D)
##### 지우개 (E)
---
##### 채우기 (F)
##### 색제거 (H) -> 지우개 + 채우기
##### 색 바꾸기 (V)
##### <img width="273" height="57" alt="image" src="https://github.com/user-attachments/assets/c2804920-8dfa-45e9-bfc2-2045de389d8f" />
##### tolerence는 칠해지는/지워지는/변경할 색의 범위
##### 높힐수록 범위가 높아진다는대..몰?루
---
##### 직선 (L) - Line
---
##### 사각형 (R) - Rectangle
##### 동그라미 (C) - Circle
##### 다각형 (P) - Polygon
##### <img width="554" height="115" alt="image" src="https://github.com/user-attachments/assets/2cfe1a70-7123-46fc-b898-8eb82f0c635c" />
##### 왼쪽부터 순서대로 - 경계선만, 안쪽 색만, 둘다, 크기, 경계선 부드러운 정도
---
##### 곡선 (A) - Arch
##### <img width="1247" height="63" alt="image" src="https://github.com/user-attachments/assets/09e9aeec-08a3-48e7-a303-8109ab9a316e" />
##### 왼쪽부터 순서대로 - 꺾이는 선 부위 부드러운 정도, 크기, 경계선 부드러운 정도
---
##### 텍스트 (T) - Text
##### <img width="499" height="64" alt="image" src="https://github.com/user-attachments/assets/bfcd9ff2-ab4f-4a22-a980-fa9b9807c035" />
##### 왼쪽부터 순서대로 - 폰트 타입, 스타일(말 그대로), 크기, 굵기
---
##### 스포이드(O)
---
##### 사각형 영역지정 (S)
##### 페인트 영역지정 (Q)
##### 마술지팡이 ```작명센스 왜이래``` (W)
##### ctrl 키 + 드래그로 다중 영역 지정 가능
##### alt 키 + 드래그로 영역 취소
---
##### 회전 (U)
##### 클립보드에 있는 것 상하/좌우 반전 (X/Y)
##### 이미지 이동 (M)
---
##### ~~솔직히 이거 누가 외움? ㅋㅋ~~
##### 그냥 버튼 클릭하자..
---
### 레이어
##### <img width="231" height="110" alt="image" src="https://github.com/user-attachments/assets/415d5999-1b96-490e-8ab8-8543ed4e30b2" />
##### 왼쪽부터 순서대로 - 레이어 생성, 레이어 그룹(폴더) 생성, 삭제
---
##### 생성 후 드래그 해서 위로 올리거나 내릴 수 있음
##### 오른쪽 클릭 후, 각 레이어 설정 가능
##### 레이어가 많아지면 레이어 그룹으로 묶어서 사용하자!
---
##### <img width="297" height="525" alt="image" src="https://github.com/user-attachments/assets/9479bfb3-e574-4da7-bb8d-e0f1ed65ec06" />

##### 레이어를 더블클릭하면 속성창이 열린다
##### 왼쪽부터 순서대로 - 이름 변경, 특수효과, 투명도 다.
---
##### <img width="54" height="72" alt="image" src="https://github.com/user-attachments/assets/5d3b21d6-35a2-40a2-8646-a15a7a28e4d2" />
##### 알다시피 가시화, 고정 기능이다.
##### 눈에 보이게/안보이게 하고,
##### 레이어에 작업을 더 이상 가능하지 않게 만드는 용도
---
### 이펙트
##### <img width="209" height="151" alt="image" src="https://github.com/user-attachments/assets/03f7a9cf-4215-4a32-b5a8-81641e80e323" />
##### 스프라이트를 블러처리, 흑백으로 바꿔준다


