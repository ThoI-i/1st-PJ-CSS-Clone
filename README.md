
# CSS Clone - [카카오](https://www.kakaocorp.com/page/)

첫 번째 프로젝트로 6일간 HTML + CSS를 활용하여 기존 페이지 제작

#### 🗓️ 프로젝트 기간: 24/10/24 ~ 24/10/29



[![GitHub Badge](https://img.shields.io/badge/ThoI－i-181717?logo=github&logoColor=white&labelColor=181717)](https://github.com/ThoI-i)
[![GitHub Badge](https://img.shields.io/badge/yujin－5-181717?logo=github&logoColor=white&labelColor=181717)](https://github.com/yujin-5)
[![GitHub Badge](https://img.shields.io/badge/parkchenui-181717?logo=github&logoColor=white&labelColor=181717)](https://github.com/parkchenui)


## Tech Stack with Tools
![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

 ![VS Code Badge](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=visual-studio-code&logoColor=white)


## **[메인 페이지](https://www.kakaocorp.com/page/)**
![메인 페이지](https://cdn.discordapp.com/attachments/1300055715003633667/1300779047084757023/image.png?ex=67221464&is=6720c2e4&hm=0e55d7e46f00ecd15d2ea56f005253598e0a3fcac5a228c244dba6b1399de305&.png.)

## **[뚝딱뚝딱 성장기](https://www.kakaocorp.com/page/story/history)**
![뚝딱뚝딱 성장기](https://cdn.discordapp.com/attachments/1300055715003633667/1301047516246310993/image.png?ex=67230e6c&is=6721bcec&hm=858b92f8cb5cdb7a0a613c29c86a1cf09117168861771bccaf96493d6f55e3f0&.png)

## **[콘텐츠 저장소](https://www.kakaocorp.com/page/story/archives)**

### 📜[회의록](https://www.notion.so/12920f09dc2a803594e0daef10f9c3a1?v=12920f09dc2a8177862c000c67077de9)

### ✒️배운점
<details>
  <summary>display: flex 사용불가 상황 아이콘만 가운데 정렬</summary>
부모를 position: relative;
자식(아이콘)을 position: absolute로 조정
</details>
<details>
  <summary>a태크 범위 늘리기 / 속성 없애기</summary>
🟢태그 범위 늘리기
부모에 display: inline-flex;
자식(a태그)에  padding + width, height 100%로 범위 늘리기

🟢속성 없애기
text-decoration: none; /* 밑줄 제거 */
color: inherit; /* 링크 색상을 부모 색상과 동일하게 설정 */
}
</details>
<details>
  <summary>Video가 재생되지 않을 시</summary>
  
  autoplay muted playsinline 추가
  
  ```html
  <video src="./img_JW/Atc1_Video.mp4" autoplay muted playsinline></video>
  ```
</details> 
<details>
<summary>박스 내 텍스트/이미지가 절반 영역하도록 설정</summary>
1. Flexbox: .img-box에 display: flex;와 flex-direction: column;을 사용하여 텍스트와 이미지를 세로로 배치합니다.
2 . flex: 1: 각 요소에 flex: 1;을 설정하여 텍스트와 이미지가 각각의 높이를 절반씩 차지하도록 합니다.
</details>
<details>
<summary>p태그 내 문장을 단락 나누기</summary>
<p> 태그 대신 <div> 태그를 사용하여 각 단락을 감싸고, CSS를 통해 스타일링하는 방법이 있습니다. margin-bottom: 16px; /* 단락 간격 조절 */
</details>


### 📌이슈
다른 브랜치 → main 브랜치 Pull requests 중 동일 파일 명이 있어 Conflict 발생

1️⃣ GitHub에서 Pull requests close → 로컬에서 문제해결 후 Pull reqeusts 재요청<br>
2️⃣ 문제 파일 명 수정 후 commit → GitHub Merge 가능으로 변경됨

### 💡느낀점
ThoI-i
- 시맨틱 구조 구성 후 CSS 작업에 진행했는데도 기눙구현을 위해 html 구조를 추가/삭제하는 경우가 발생 → 추후 작업 시 면밀한 구조 설계 필요성 체감
- 배율 확대/축소 시 페이지 구조 흐트러짐 → 사용자 환경에 따른 반응형(미디어쿼리) 제작 필요성 확인
- 유연한 사고 방식의 필요성<br>flex-direction: column; 을 통해 세로 배치 가능함, 해당 기능 잊어서 postion: relative + absolute만 사용.

yujin-5
- html을 완성했다고 생각했는데 css를 하면서 다시 수정하는 일이 발생했고 이를 통해 변경에 유연한 코드 구조를 설계하는 것에 대해 생각해보게 됨.
- 비슷한 레이아웃의 경우 같은 클래스나 아이디를 부여하는 것이 효과적으로 작업 시간을 줄일 수 있다는 것을 체감함.

parkchenui
