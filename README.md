# FarmLive


Json까지는 다운로드 한 상태, JSON 이후에 인벤토리가 개수에 따라 들어맞는지만 확인해보자.

오늘 대략적으로 할것

############## 지금 인벤토리가 너무 비워있는것처럼 보임 ( 씨앗, 작물, 물건) 으로 나누어져 있는데 2가지 종류로 나누자.

현재 - 총 8개
씨앗 - 토마토 씨앗, 딸기 씨앗, 샤인머스켓 씨앗 - 3개
작물 - 토마토, 딸기, 샤인머스켓 - 3개
물건 - 물뿌리개, 오토바이 - 2개

변경 예정 - 15개씩 2개 생각중
작물 - 토마토 씨앗, 딸기 씨앗, 샤인머스켓 씨앗, 토마토, 딸기, 샤인머스켓, 꽃 (몇개 인지 모른다.)
물건 - 물뿌리개, 오토바이, 나뭇가지?, 메모장?, 퀘스트할때 NPC용 선물(3개 정도), 지도?

일단은 이정도로 생각하고 에셋을 찾아보고 생각해야할듯 하다.
지금 인벤을 보면 아이템이 있는곳만 슬롯이 나오는데 슬롯은 전부가 나오고 아이템이 나오게 해야할듯하다.

- 인벤토리
  아이템을 주으면 템이 순서대로 가져와지고, 아이템에 몸이 닿으면
  마우스 드래그로 아이템 위치 변경가능

마우스를 갖다대면 부연설명 창이 나온다.
설명과 아이템 개수가 나온다. - 이것들은 하자. 

아이템 얻기 , 삭제 - 퀘스트, 농사로 아이템 얻거나,    삭제는 인벤토리에 휴지통 아이콘 같은것 만들자.

아이템이 생기면 아이템 앞면에 나오게 된다. - 이거는 나중에 수정해보자.

수정할만한것
- 에셋들
- UI - 화면 - 나중에 이미지만 따로 수정해보자. 가방 아이콘이 맞는게 안보인다. 
- 미니맵, 설정(종료버튼, 음향버튼 이정도 ex - 화면 비율?????)
- 가운데 위에 현재 시간이나, 현재 있는 곳에 장소 같은것을 알려주는 텍스트 있어도 좋을 듯

-------------------------------------------------------

해야할것
- 기본 UI화면 제작 - 대략적 완료
- 싱글톤 ( 다른 씬으로 이동하는 것 )
- 웹페이지 연결
- 날씨 기능
- 인벤토리
- 농사 - 인벤토리에서 씨앗 꺼내서 사용하게 하자.
- 자전거 기능
- 퀘스트
- 
일단 이정도

gpt 한테 물어본 순서 

1. 인벤토리
2. 농사
3. 자전거 기능
4. 퀘스트
5. 싱글톤

