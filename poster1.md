대학 수습기자 모집 포스터를 보고 CSS로 그대로 만들어보는 프로젝트를 진행하였다.

## **CSS 프로젝트 보고서**

### **개요**

이 보고서는 대학언론사의 수습기자 모집을 위한 웹 페이지를 CSS로 디자인하는 프로젝트에 대한 내용을 다룬다. 프로젝트는 웹 페이지의 디자인과 레이아웃을 개선하여 사용자 경험을 향상시키는 것을 목표로 한다.

### **목표**

- 웹 페이지의 시각적인 요소를 개선한다.
- CSS 스타일을 통해 웹 페이지의 레이아웃을 개선하고 사용자가 정보를 쉽게 찾을 수 있도록 한다.

### **기술적인 세부사항**

- HTML과 CSS를 사용하여 웹 페이지의 디자인을 구현한다.
- CSS 스타일을 통해 배경색, 폰트 스타일, 간격 등을 조정하여 페이지를 더 보기 좋게 만든다.
- 이미지를 삽입하고 CSS를 활용하여 이미지의 위치와 스타일을 조정한다.
- 리스트 스타일을 변경하여 목록을 보기 좋게 표시한다.
- 페이지 내의 각 섹션마다 적절한 스타일을 적용하여 내용을 구분한다.

### **주요 기능**

1. **색상과 스타일**: 배경색, 글자색, 폰트 스타일 등을 조정하여 페이지의 시각적인 효과를 개선한다.
2. **이미지 조정**: 이미지의 위치와 크기를 조정하여 페이지 레이아웃을 깔끔하게 만든다.
3. **목록 스타일링**: 리스트 스타일을 변경하여 목록을 시각적으로 구분한다.

### **실행 및 테스트**

1. 웹 페이지를 브라우저에 로드하여 디자인 및 레이아웃을 확인한다.
2. 다양한 디바이스 크기에서 페이지가 잘 보이는지 확인하여 반응형 디자인을 테스트한다.
3. 이미지의 위치 및 스타일, 리스트의 스타일 등을 다양한 환경에서 테스트하여 사용자 경험을 향상시킨다.

### **결론**

이 프로젝트를 통해 웹 페이지의 디자인을 개선하고 사용자가 정보를 쉽게 이해하고 접근할 수 있는 환경을 제공하였다. CSS를 활용하여 다양한 스타일링을 적용시 웹 페이지를 보다 매력적으로 만들었다.

---

```Html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: rgb(34, 14, 83);
            margin: 0;
            padding: 0;
        
        }

        #content {
            margin-left: 20%;
            padding: 20px;
        }

        .title {
            color: white;
            font-weight: bold;
            font-size: 30pt;
        }

        .subtitle {
            color: yellow;
            font-size: 20pt;
            font-style: italic;
        }

        .section {
            font-size: 15pt;
            color: skyblue;
            margin-bottom: 20px; /* 섹션 간격 추가 */
        }

        .section>ul {
            font-size: 12pt;
            list-style-type: none; /* 동그라미 제거 */
            padding-left: 50px; /* 들여쓰기 추가 */
            font-family: 'Gungsuh', serif; /* 궁서체 글꼴 지정 */
        }

        .center {
            text-align: center; /* 이미지 중앙 정렬 */
            margin-bottom: 20px; /* 이미지 아래 간격 추가 */
        }

        .right-bottom {
            position: fixed;
            bottom: 20px;
            right: 20px;
        }

        /* 첫 번째 이미지 오른쪽 마진 조정 */
        #first-image {
            margin-right: 300px; /* 오른쪽 마진 추가 */
        }
    </style>
</head>

<body>

    <div id="content">
        <h1 class="title">대학언론사 수습기자 모집</h1>
        <h2 class="subtitle">신입생 여러분을 기다립니다</h2>
        <div class="center">
            <!-- 첫 번째 이미지에 ID 추가 -->
            <img src="C:\Users\ms\Desktop\html\onair.png" alt="" id="first-image">
        </div>
        <div class="section">
            <h3>모집분야</h3>
            <ul>
                <li>아나운서(0명) : 학내 소식을 라디오 방송으로 보도</li>
                <li>오프닝쇼프로듀서(0명) : 라디오 방송 기획, 제작</li>
                <li>엔지니어(0명) : 라디오 방송 녹음 및 편집</li>
            </ul>
        </div>
        <div class="section">
            <h3>혜택</h3>
            <ul>
                <li>수습기자 활동 중 소정의 활동비 지급</li>
                <li>정기자로 진급하면 장학금 지급</li>
            </ul>
        </div>
        <img src="C:\Users\ms\Desktop\html\mic.png" alt="" class="right-bottom">
    </div>
</body>

</html>
```

<img width="661" alt="스크린샷 2024-04-12 154240" src="https://github.com/dawoon1229/CSS_project/assets/164113758/5dc9d58f-4929-42f2-a7bd-346563751051">


