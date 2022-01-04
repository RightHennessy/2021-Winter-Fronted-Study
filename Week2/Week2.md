# Week2

- JavaScript 개요

<br>
<details>
<summary> 단축키 </sumary>
    <div markdown = "1">
    웹으로 연결하기 `Alt` + `B` <br>
    개발자 도구 `ctrl` + `shift` + `I`
</div>
</details>


<br>

## JavaScript 특징
prototype 기반 언어 - [참고자료](https://medium.com/@limsungmook/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EB%8A%94-%EC%99%9C-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85%EC%9D%84-%EC%84%A0%ED%83%9D%ED%96%88%EC%9D%84%EA%B9%8C-997f985adb42) <br>
느슨한 타입과 엄격하지 않은 실행 <br>
높은 확장성 

<br>

## script 태그
```html
<body>
    <script>
        console.log('Hello')
    </script>
</body>
```

<br>

## 변수와 함수

<br>

`var` 지역 및 전역 변수 선언, 유동적으로 할당 값 변경 가능 <br>
`let` 블록 범위 지역 변수 선언, 변수에 재할당 가능 (재선언 불가능) <br>
`const` 변수 재선언 및 재할당 불가능 <br>
`function` 함수 생성 <br>
```javascript
    const func01 = function(param){
            console.log('hello fun01 and', param)
        }
        func01('param01')
```

<br>

## 반복문, 조건문
생략

<br>

## DOM 제어

<br>
DOM = document - HTML <br>

[참고자료](https://grace-go.tistory.com/78)

<br>

## 과제
1. [별찍기 구현](https://github.com/RightHennessy/2021-Winter-Fronted-Study/blob/main/Week2/assignment.html)

2. JavaScript 이벤트리스너 종류
<br>
[이벤트 리스너란?](https://ordinary-code.tistory.com/64) <br>
[이벤트 리스너 종류](https://yoonjong-park.tistory.com/entry/addEventListener-%EC%9D%B4%EB%B2%A4%ED%8A%B8%EB%A6%AC%EC%8A%A4%EB%84%88-%EC%A2%85%EB%A5%98)


3. Git, Github 개념 조사 - [참고자료](https://velog.io/@gparkkii/GitGithub)

4. Github Desktop 설치