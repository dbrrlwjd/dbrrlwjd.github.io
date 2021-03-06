# 숨바꼭질

1. 게임소개
2. 주차별 개발현황

---

## 게임소개

 - 게임명 : 숨바꼭질
 - 장르 : 퍼즐, 캐주얼
 - 개발엔진 : Unity3D
 - 조작키 : WASD, ctrl
 - 게임설명 : 제한시간 내에 숨어있는 아이들을 찾아야 하는 게임입니다.   
 숨어있는 아이들을 다 찾으면 점수가 더해지고 다음 라운드로 진행되며 난이도가 상승합니다.    
 중간중간 숨어있는 장소에 대한 단서가 나타나기도 하며, 어떨 때는 아이템을 사용해야만 합니다.

## 주차별 개발현황   

### 1주차 : 계획서 작성   

### 2주차 : 맵 제작과 주인공 캐릭터   
바닥과 벽을 세우고 주인공 캐릭터를 배치하였다.   
캐릭터 이동 스크립트와 콜라이더 등을 설정하였다.   
<img src="./imgs/벽.png" width="450px" height="300px"></img>
   
개발과제 : 숨어있는 캐릭터를 찾았을 때의 상호작용 스크립트가 필요  

### 3주차 : 상호작용 스크립트 구현  
상호작용 스크립트를 구현하였다. 문을 클릭하면 여닫을 수 있다.   
<img src="./imgs/click.png" width="450px" height="300px"></img>   
캐릭터를 클릭하면 "click"이라는 문자열이 출력된다.   
아직 캐릭터 에셋이 없어 3D오브젝트로 대체하였다.   
   
개발과제 : 맵 제작 및 캐릭터 에셋 필요     

### 4주차 : 맵 제작   
맵 제작이 거의 완료되었다.   
<img src="./imgs/맵.png" width="450px" height="300px"></img>   
캐릭터 에셋이 추가되었다.   
<img src="./imgs/캐릭터에셋.png" width="450px" height="300px"></img>   

개발과제 :    
맵 제작 마무리(라이트 추가, 문이나 선반 등의 오브젝트에 스크립트 설정)   
캐릭터 이동 스크립트 수정 필요(WASD로 이동, 마우스로 카메라 회전, 웅크리기 기능 구현 필요)   

### 5주차 : 스크립트 수정   
맵 제작 마무리   
<img src="./imgs/라이트.png" width="450px" height="300px"></img>   
WASD로 이동하고 카메라가 마우스 커서를 따라 회전하도록 수정   

개발과제 :    
오브젝트와 상호작용할 때 거리와 관계없이 상호작용 되는 문제 확인   
마우스로 화면이 회전할 때 부자연스러움, 크로스헤어로 변경 필요   
웅크리는 애니메이션 필요

### 6주차 : 스크립트 수정   
일정 거리 내에서만 오브젝트와 상호작용할 수 있도록 수정   
마우스커서->크로스헤어로 변경   
<img src="./imgs/크로스헤어.png" width="450px" height="300px"></img>   
   
개발과제 :    
좌우(AD)이동시 애니메이션이 움직이지 않는 문제 확인   
웅크리는 애니메이션 필요      

### 7주차 : 중간평가

### 8주차 : 애니메이션 수정
좌우(AD)이동시 애니메이션이 움직이지 않는 문제 수정   
웅크리는 기능 구현   
<img src="./imgs/웅크리기.png" width="450px" height="300px"></img>   

개발과제 : 
벽 끼임 문제 확인

### 9주차 : 라운드 시스템 구현   
클릭하면 씬을 전환할 수 있도록 구현   
스카이박스 추가   
<img src="./imgs/스카이박스.png" width="450px" height="300px"></img>   

개발과제 :    
조건을 만족해야 씬을 전환할 수 있도록 수정 필요

### 10주차 : UI 구현
UI 구현   
숨겨져 있는 오브젝트에 크로스헤어를 갖다대면 강조표시 되도록 구현   
<img src="./imgs/유아이.png" width="450px" height="300px"></img>   

개발과제 :    
UI 스크립트 작성 필요   
raycast가 벽 가장자리를 통과하는 문제   

### 11주차 : 튜토리얼
간단한 튜토리얼 제작   
<img src="./imgs/튜토리얼.png" width="450px" height="300px"></img>   

개발과제 :    
물리엔진 오류로 벽을 뚫는 버그 확인

### 12주차 : 버그 수정   
벽을뚫는 버그 수정    

개발과제 :    
애니메이션이 작동하지 않는 버그 발견

### 13주차 : 스테이지 구현   
스테이지 구현 및 찿은 동물을 표시해주는 기능 구현    
<img src="./imgs/인터페이스.png" width="450px" height="300px"></img>     

### 14주차 : 사운드 추가     
배경음악과 동물을 찿았을 때 효과음 추가

### 14주차 : 최종조정   
테스트 플레이 및 버그 수정

