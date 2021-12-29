# Week1

- Web 개발 개요
- HTML, CSS 기초 학습

<br>

## Web
[Web Fronted 로드맵](https://smoh.tistory.com/388)

<br>

## HTML
 - html 구조

    ```html
    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="uft8"/>
        </head>
        <body>
            Hello, World!
        </body>
    <html>
    ```

<br>

- html 필수 태그
    - `<div></div>` : 의미 X, 컨텐츠들을 묶어야 할 때 사용, block level element
    - `<span></span>` : 의미X, 컨텐츠들을 묶어야 할 때 사용, inline level element
    - `<a></a>` : anchor, 웹 페이지나 외부 사이트로의 연결, 널링크(href="#)
    - `<ul> <li> </li> </ul>` : `<li>` - `<ul>`과 `<ol>` 내에서 각 항목을 나열할 때 사용, `<ul>` - unordered list
    - `<input />` : form 요소, 사용자가 정보입력 가능  
    - `<button></button>` : 버튼
    <details>
    <summary> meta </summary>
    <div markdown="1">       

    '메타(meta)'라는 용어는 IT분야에서는 주로 메타데이터의 의미로 사용되어 왔다. <br>
    그것은 그리스어의'μετα(meta)'로부터 유래된 말로 "after", "beyond", " with", "adjacent", "self" 등의 의미로 사용되는 접두사(prefix)로서, 보통은 위와 같은 일반적인 의미로 사용되나, 이 용어가 오랜 기간을 거치는 동안 라틴어를 거쳐 영어권으로 오면서 철학적인 개념으로 발전되어,『 다른 개념의 추상(抽象)으로서의 개념(槪念)』을 나타내는 접두어로 사용되기에 이르렀다.<br><br>
    메타데이터 (Metadata)란 데이터(Data)를 위한 데이터이다.<br>
    어떤 데이터, 즉 구조화된 정보를 분석, 분류하고 부가적 정보를 추가하기 위해 그 데이터 뒤에 함께 따라가는 정보를 말한다. 이를테면, 디지털 카메라에서는 사진을 찍어 기록할 때마다 카메라 자체의 정보와 촬영 당시의 시간, 노출, 플래시 사용 여부, 해상도, 사진 크기 등의 사진 정보를 화상 데이터와 같이 저장하게 되어 있다.


    </div>
    </details> 

<br>

- html 태그 속성 <br>
    -> 요소에 대한 추가적인 정보 제공
    - id : 요소에 대한 id를 명시, #id_name
    - class : 요소에 대한 클래스를 그룹으로 묶어 스타일을 지정, .class_name 
    - style : 요소에 대한 inline CSS style 을 명시


<br>

## CSS
- CSS 꾸미기 필수 속성
    - width, height
    - margin, padding
    - background-color, border, border-radius
    - font-size, color

<br>

- CSS 배치 필수 속성
    - display : flex;
    - flex-direction : row, reverse-row, column, reverse-column;    <br>-> 가로 or 세로 결정
    - justify-content : flex-start, center, flex-end;
        <br> -> 가로정렬
    - align-items : flex-start, center, flex-end;
        <br> -> 세로정렬

<br>

참고자료 : [CSS 속성 종류](https://potionstory.tistory.com/12) <br>
참고자료 : [Flexbox Frog](https://flexboxfroggy.com/#ko)

<br>

## 과제
1. html 태그와 속성과 기능 조사하기
2. Flexbox Frog 24단계까지 완성
3. CSS 종류 5개 이상 조사하기
4. HTML 파일에서 JavaScript 실행 방법 조사하기  - [HTML JavaScript 실행 방법](https://zion830.tistory.com/29) <br>
JavaScript의 변수, 함수 개념 - [변수](https://jenny-daru.tistory.com/7?category=901193), [함수](https://jenny-daru.tistory.com/12?category=901193)