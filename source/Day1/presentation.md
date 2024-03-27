---
marp: true
paginate: true
theme: default
---

![bg](../cover.png)

---

# **Day 1 Contents**

### 1. 웹의 3요소

### 2. HTML

### 3. CSS 기초

### 4. 과제

---

# 1. 웹의 3요소

---

# **HTML**, **CSS**, **Javascript**

---

## **HTML (HyperText Markup Language)**

### 웹 페이지의 구조와 내용을 정의하는 마크업 언어

- 브라우저에 표시되는 웹 페이지의 뼈대 역할
- 다양한 태그를 사용하여 문서의 구조를 만듦

---

**주요 태그 예시**

```html
<h1>제목(Heading) 태그</h1>
    <p>: 문단(Paragraph) 태그</p>
    <div> : 구역 나누기(Division) 태그
      <img /> : 이미지 삽입 태그
      <a> : 하이퍼링크 태그 </a>
    </div>
</h1>
```

---

## **CSS (Cascading Style Sheets)**

### HTML 요소의 스타일과 레이아웃을 정의하는 스타일시트 언어

- HTML로 만든 뼈대를 시각적으로 꾸며주는 역할
- 선택자(Selector)를 사용하여 특정 HTML 요소에 스타일 적용

---

**주요 속성 예시**

```css
color            : 텍스트 색상 지정
background-color : 배경 색 지정
font-size        : 글자 크기 지정
margin           : 바깥 여백 지정
padding          : 안쪽 여백 지정
```

---

## **Javascript**

### 웹 페이지에 동적인 기능을 추가하는 프로그래밍 언어

- 사용자와의 상호작용, 동적 효과, 데이터 처리 등의 기능 구현
- HTML 요소를 조작하고 이벤트에 반응

---

**주요 기능 예시**

- 버튼 클릭 시 특정 동작 수행
- 폼 데이터 유효성 검사
- 애니메이션 효과 적용
- 서버와 비동기 통신(AJAX)
- DOM(Document Object Model) 조작

---

# 2. HTML

---

## HTML 문서 구조

```html
<!DOCTYPE html>
<html>
  <head>
    <title>문서 제목</title>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>큰 제목</h1>
    <p>단락 내용</p>
    <script src="script.js"></script>
  </body>
</html>
```

---

- `<!DOCTYPE html>` : HTML5 문서 타입 선언
- `<html>` : HTML 문서의 루트 요소
- `<head>` : 문서 메타데이터 정의(제목, 인코딩, 스타일시트, 스크립트 등)
- `<body>` : 문서의 본문 내용 작성

---

## 주요 HTML 태그

- `<h1>` ~ `<h6>` : 제목(Heading) 태그. 숫자가 커질수록 글자 크기가 작아짐
- `<p>` : 문단(Paragraph) 태그
- `<a href="URL">` : 하이퍼링크 태그. href 속성에 링크 URL 지정
- `<img src="URL" alt="대체텍스트">` : 이미지 태그. src 속성에 이미지 URL 지정
- `<ul>`, `<ol>`, `<li>` : 리스트(List) 태그. ul은 순서없는 리스트, ol은 순서있는 리스트
- `<div>` : 구역 나누기(Division) 태그. 레이아웃 구성에 주로 사용
- `<span>` : 인라인 구역 태그. 텍스트 일부에 스타일 적용 시 사용

---

# 3. CSS 기초

---

## CSS 문법

```css
선택자(selector) {
  속성(property): 값(value);
}
```

- 선택자(selector) : 스타일을 적용할 HTML 요소 지정
- 속성(property) : 스타일 속성
- 값(value) : 속성에 적용할 값

**예시**

```css
p {
  color: red;
  font-size: 16px;
}
```

---

## CSS 적용 방법

1. 인라인(Inline) 방식
   - HTML 요소의 style 속성에 직접 스타일 작성

```html
<p style="color: red;">단락 내용</p>
```

---

2. 내부(Internal) 방식
   - HTML 문서 내부에 `<style>` 태그를 사용하여 스타일 작성

```html
<head>
  <style>
    p {
      color: red;
    }
  </style>
</head>
```

---

3. 외부(External) 방식
   - 별도의 CSS 파일에 스타일을 작성하고 HTML 문서에서 연결

```html
<head>
  <link rel="stylesheet" href="style.css" />
</head>
```

```css
/* style.css */
p {
  color: red;
}
```

---

# 4. 과제

## **HTML, CSS를 사용하여 간단한 자기소개 페이지 만들기**

- 이름, 소개, 관심사 등의 내용 포함
- 외부 스타일시트 사용

---

# 다음 시간에 계속...
