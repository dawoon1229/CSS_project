## CSS 클론 코딩

맥도날드 키오스크 화면을 CSS로 만들어 보았다.

---

### **보고서: 맥도날드 키오스크 화면 클론 코딩**

---

### **1. 개요**

이 프로젝트는 맥도날드 키오스크 화면을 클론 코딩하여 구현하는 것을 목표로 한다. 클론 코딩을 통해 HTML과 CSS를 사용하여 맥도날드의 키오스크 화면을 재현하고, 이를 통해 웹 디자인 및 프론트엔드 개발 능력을 향상시키는 것이 목표이다.

---

### **2. 목표**

- 맥도날드 키오스크 화면의 UI/UX를 완벽히 재현한다.
- Flexbox를 사용하여 레이아웃을 조정하고 반응형 디자인을 구현한다.
- CSS 스타일링을 통해 디자인의 일관성을 유지하고 시각적 효과를 추가한다.

---

### **3. 기술적인 세부사항**

- HTML과 CSS를 사용하여 웹 페이지를 구현한다.
- Google Fonts의 'Noto Sans KR' 폰트를 사용하여 한글 텍스트를 표시한다.
- Flexbox를 사용하여 레이아웃을 조정하고 요소들을 정렬한다.
- 이미지 요소를 삽입하고 CSS를 통해 스타일을 적용한다.
- 호버 효과를 사용하여 마우스 오버 시 시각적 변화를 제공한다.

---

### **4. 주요 기능**

- 키오스크 화면 상단에는 맥도날드 로고와 메뉴 타이틀이 표시된다.
- 추천 메뉴, 시그니처 버거, 버거 & 세트, 스낵 & 사이드, 음료, 디저트 등의 카테고리를 사이드바에 표시한다.
- 메뉴 아이템은 이미지, 제목, 가격 정보를 포함하고 호버 효과를 적용하여 시각적 효과를 제공한다.

---

### **5. 실행 및 테스트 결과**

- 코드를 실행하여 웹 브라우저에서 확인할 수 있으며, 반응형 디자인을 확인하기 위해 다양한 디바이스에서 테스트한다.
- 레이아웃이 유연하게 조정되고 호버 효과가 정상적으로 작동하는지 확인한다.

---
```Html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>flex</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <div id="topImg">키오스피킹</div>
    </header>
    <div id="titlebar">
        <div>
            <img class="logo" src="https://blog.kakaocdn.net/dn/w1UK3/btqwTx0mNVX/ki6E4Mva5YavwrOFJQkCP1/img.jpg" alt="">
        </div>
        <div id="title">
            <h1>추천 메뉴</h1>
            <button>이전</button>
        </div>
    </div>
    <div id="content">
        <div id="sidebar">
            <div>추천 메뉴</div>
            <div>시그니처버거</div>
            <div>버거&세트</div>
            <div>스낵&사이드</div>
            <div>음료</div>
            <div>디저트</div>
        </div>
        <div id="menus">
            <div>
                <div class="menu-item">
                    <img src="https://i.namu.wiki/i/Ygn4fpp-uJ-qrRrXkR164u-M0J5w9yMWA3T4ZtXPj4W9s3NDWjTibgATcV0McihbXqG0kcAJz2y8i1ARCHsamw.webp"
                        alt="">
                    <h3>베이컨토마토디럭스</h3>
                    <h4>7,500원</h4>
                </div>
            </div>
            <div>
                <div class="menu-item">
                    <img src="https://i.namu.wiki/i/Ygn4fpp-uJ-qrRrXkR164u-M0J5w9yMWA3T4ZtXPj4W9s3NDWjTibgATcV0McihbXqG0kcAJz2y8i1ARCHsamw.webp"
                        alt="">
                    <h3>베이컨토마토디럭스</h3>
                    <h4>7,500원</h4>
                </div>
            </div>
            <div>
                <div class="menu-item">
                    <img src="https://i.namu.wiki/i/Ygn4fpp-uJ-qrRrXkR164u-M0J5w9yMWA3T4ZtXPj4W9s3NDWjTibgATcV0McihbXqG0kcAJz2y8i1ARCHsamw.webp"
                        alt="">
                    <h3>베이컨토마토디럭스</h3>
                    <h4>7,500원</h4>
                </div>
            </div>
            <div>
                <div class="menu-item">
                    <img src="https://i.namu.wiki/i/Ygn4fpp-uJ-qrRrXkR164u-M0J5w9yMWA3T4ZtXPj4W9s3NDWjTibgATcV0McihbXqG0kcAJz2y8i1ARCHsamw.webp"
                        alt="">
                    <h3>베이컨토마토디럭스</h3>
                    <h4>7,500원</h4>
                </div>
            </div>
            <div>
                <div class="menu-item">
                    <img src="https://i.namu.wiki/i/Ygn4fpp-uJ-qrRrXkR164u-M0J5w9yMWA3T4ZtXPj4W9s3NDWjTibgATcV0McihbXqG0kcAJz2y8i1ARCHsamw.webp"
                        alt="">
                    <h3>베이컨토마토디럭스</h3>
                    <h4>7,500원</h4>
                </div>
            </div>
            <div></div>
        </div>
    </div>

</body>

</html>
```
```Css
@import url(https://fonts.googleapis.com/earlyaccess/notosanskr.css);

body {
    min-width: 1600px;
    margin: 0;
}

body * {
    font-family: 'Noto Sans KR';
}

header {
    height: 500px;
    background-color: #C42D1C;
    margin-bottom: 100px;
}

header #topImg {
    height: 100%;
    
    margin: auto;
    background-image: url("https://res.heraldm.com/content/image/2023/12/22/20231222000223_0.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;

    display: flex;
    align-items: center;
    justify-content: center;

    color: white;
    font-size: 60pt;
    text-align: center;
    text-shadow: 2px 2px 10px black;
}

#titlebar {
    display: flex;
    justify-content: center;
}

#titlebar>div:first-child {
    text-align: center;
    width: 250px;
}

#titlebar #title {
    width: 80%;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
}

#titlebar .logo {
    width: 200px;
}

#titlebar #title h1 {
    margin: 0px;
    margin-left: 70px;
    font-size: 60pt;
}

#titlebar #title button {
    background-color: rgb(0, 81, 0);
    color: white;
    padding: 20px;
    font-size: 26pt;
    border-radius: 10px;
    margin-right: 70px;
}

#content {
    display: flex;
    justify-content: center;
}

#sidebar {
    width: 250px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

#sidebar>div {
    border: 2px solid gray;
    width: 200px;
    height: 200px;
    text-align: center;
    font-size: 20pt;
    font-weight: bold;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 25px;
    margin: 10px;
}

#sidebar>div:hover {
    background-color: black;
    color: white;
    cursor: pointer;
}

#menus {
    width: 80%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    align-items: flex-start;
}

#menus>div {
    flex: 0 1 33%;
    display: flex;
    justify-content: center;
}

#menus .menu-item {
    width: 400px;
    height: 600px;
    border: 1px solid gray;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
}

#menus .menu-item:hover {
    background-color: #dfdfdf;
}

#menus .menu-item>img {
    width: 100%;
    height: 300px;
    margin-bottom: 30px;
}

#menus .menu-item>h3 {
    font-size: 30pt;
    margin: 0px;
}

#menus .menu-item>h4 {
    font-size: 26pt;
    margin: 0px;
}
```
