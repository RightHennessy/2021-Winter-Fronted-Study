# Week3

<br>

## 이벤트 리스너 click
```html

<body>
    <h1 id = "hello"> Hello World </h1>

    <script>
        const hello = document.querySelector('#hello')

        // hello 자체에 이벤트 리스너 추가
        hello.addEventListener('click', (e) => {
            console.log(e)
            alert('Click')
        })

    </script>
</body>

```
<br>


## 이벤트 리스너 scroll
```html
<body>
    <h1 id = "hello" style="height:200vh;">Hello World</h1>

    <script>
        const hello = document.querySelector('#hello')

        // window 에 이벤트 리스너 추가
        window.addEventListener('scroll', (e) =>{
            console.log(e)
        })
    </script>
</body>

```

<br>

## 가위바위보 만들기

`getElementById()` id를 통해 엘리먼트 반환 <br>
`querySelctor()` selector의 구체적인 그룹과 일치하는 document 안 첫번째 엘리먼트 반환 <br>
랜덤함수 생성 : Math.floor(Math.random()*(max-min+1)) + min

<br>

## 클래스형 컴포넌트 vs 함수형 컴포넌트

[참고자료](https://sohyunsaurus.tistory.com/19?category=973091)

<br>


## 과제
1. [가위바위보 게임 실습](https://github.com/RightHennessy/2021-Winter-Frontend-Study/blob/main/Week3/rockscissorspaper.html)
2. 웹 프론트엔드 및 Vue 조사 - [참고문서](https://www.samsungsds.com/kr/insights/frameworks.html)
