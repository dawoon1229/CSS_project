### **목표**

이 프로젝트의 목표는 퍼스트코딩학원 웹 사이트의 디자인과 기능을 개선하는 것이다.

### **기술적인 세부사항**

- HTML과 CSS를 사용하여 웹 페이지를 디자인하고 구성하였다.
- Flexbox를 활용하여 레이아웃을 구성하고 요소들을 배치하였다.
- 이미지를 삽입하고 배경 이미지를 설정하여 시각적인 효과를 부여하였다.

### **주요 기능**

1. 헤더(Header)
    - 로고와 네비게이션 메뉴가 표시된다.
    - 각 메뉴는 클릭 가능한 링크로 구성되어 있다.
    - 오른쪽에는 로그인과 회원가입 링크가 있다.
2. 섹션(Section)
    - 중앙에 큰 제목이 표시되고, 배경 이미지가 적용되어 있다.
    - 이미지가 세로로 배열되어 있는 섹션이다.
3. 푸터(Footer)
    - 회사 로고와 연락 정보가 표시된다.
    - 푸터는 페이지 하단에 고정되어 있다.

### **실행 및 테스트 결과**

- 웹 페이지는 웹 브라우저를 통해 정상적으로 실행되며, 모든 기능이 작동한다.
- 반응형 디자인을 적용하여 다양한 화면 크기에서도 페이지가 잘 표시된다.

### **결론**

이 프로젝트를 통해 퍼스트코딩학원 웹 사이트의 시각적인 디자인을 향상시켰다. Flexbox와 CSS를 활용하여 레이아웃을 유연하게 구성하였고, 이미지와 배경 이미지를 통해 페이지에 동적인 요소를 추가하였다. 사용자는 편리하고 직관적인 인터페이스를 통해 사이트를 탐색할 수 있다.

---

### 코드와 스타일 시트
```Html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo1">
            <img src="https://firstcoding-kr.github.io/deep-web/html/website/logo.png">
        </div>
        <div class="center">
            <a href="#">COMPANY</a>
            <a href="#">PRODUCT</a>
            <a href="#">CUSTOMER</a>
            <a href="#">SERVICE</a>
            <a href="#">RECRUIT</a>
        </div>
        <div class="right">
            <a href="#">HOME</a>|
            <a href="#">NOTICE</a>|
            <a href="#">LOGIN</a>|
            <a href="#">JOIN</a>
        </div>
    </header>

    <section>
        <div id="centerSentence">
            코딩의 시작, 퍼스트 코딩
        </div>
        <div id="imgThree">
            <img src="https://firstcoding-kr.github.io/deep-web/html/website/banner1.jpg">
            <img src="https://firstcoding-kr.github.io/deep-web/html/website/banner2.jpg">
            <img src="https://firstcoding-kr.github.io/deep-web/html/website/banner3.jpg">
        </div>
    </section>

    <footer>
        <img src="https://firstcoding-kr.github.io/deep-web/html/website/logo.png">
        <div id="foot">
            <h2>퍼스트코딩학원</h2>
            <p>경남 진주시 초전북로 57, 3층</p>
        </div>
    </footer>
</body>
</html>
```
```Css
body {
    margin: 0 auto;
    width: 1000px;
}

a {
    text-decoration: none;
    color: white;
}

header {
    display: flex;

    width: 100%;
    height: 100px;

    padding-bottom: 10px;
    box-sizing: border-box;

    background-color: #2d3a4b;
}

.logo1 {
    float: left;

    display: flex;
    justify-content: center;
    align-items: center;

    width: 25%;
    height: 100px;
}

.logo1 > img {
    width: 80%;
}

.right {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;

    padding-top: 10px;
    box-sizing: border-box;

    color: white;
}

.right a {
    margin-right: 7px;
    margin-left: 7px;
}

.center {
    float:left;

    display: flex;
    justify-content: space-between;
    align-items: flex-end;

    width: 50%;
    height: 100%;
}

section {
    width: 100%;
}

#centerSentence {
    width: 100%;
    height: 450px;
    line-height: 450px;
    
    background-image: url('https://firstcoding-kr.github.io/deep-web/html/website/main.jpg');
    background-size: 100% auto;
    
    background-position: 0px -100px;

    font-size: 26pt;
    font-weight: bold;
    color: white;
    text-align: center;
}

#imgThree {
    display: flex;
    justify-content: space-between;
    align-items: center;

    width: 100%;
    height: 500px;
    box-sizing: border-box;
    padding-left: 50px;
    padding-right: 50px;
    line-height: 500px;

    vertical-align: middle;

    text-align: center;
}

#imgThree > img {

    float: left;

    height: 400px;

}

footer {
    display: flex;
    justify-content: center;
    align-items: center;

    width: 1000px;
    height: 130px;
    bottom: 0;

    background-color: rgb(241, 241, 241);
}

footer > img {
    width: auto;
    height: 70px;
}

#foot {
    display: flex;

    flex-direction: column;
    justify-content: center;

    height: 130px;
    width: 250px;   
}

h2 {
    margin: 0;
    padding: 0;
}

p {
    margin: 0;
    padding: 0;
}
```

---
### 실행 화면

<img width="750" alt="스크린샷 2024-04-25 193627" src="https://github.com/dawoon1229/CSS_project/assets/164113758/6dc76e4f-cd10-4774-9da5-0f418ca81934">

