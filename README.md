# 제목(Header)

띄어쓰기 중요(권장)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하나님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록 (띄어쓰기2번)  
하나님이 보우하사 우리나라 만세 (br태그)<br/>
무궁화 삼천리 화려 강한
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_ (\*앞뒤로추가)<br/>
**두껍게**(**앞뒤로추가)  
\***이텔릭+두껍게**_(_**앞뒤로추가)  
~~취소선~~(~~앞뒤로추가)  
<u>밑줄</u>(u태그 앞뒤로 열고 닫아줌)

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록  
      (들여쓰기 2번 즉 띄어쓰기 총4번 되어있으면 이렇게 들여써짐)
1. 순서가 필요한 목록  
   (숫자1.만 앞에 넣고 띄어쓰기 하고 쓰면 알아서 순서정해줌)

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록  
  (-후 띄어쓰기 한다음 쓰면됨)

# 링크(Lings)

<a href="http://naver.com">네이버</a>
(html에서 a태그 하듯이)  
[NAVER](http://naver.com)
(대괄호[]안에 페이지이름 바로뒤에 ()소괄호에 주소)  
<a href="http://naver.com" title="NAVER로 이동">네이버</a>
(타이틀 추가)  
[NAVER](http://naver.com "NAVER로 이동")
(소괄호 안에 주소넣은거 뒤 띄어쓰기하나하고 ""큰따움표 안에 내용이 타이틀)  
<a href="http://naver.com" title="NAVER로 이동" target="_blank">네이버</a>
(타겟은 a태그로만 가능 마크다운에서는 타겟\_blank를 지원하지 않음(원시a태그로해야함))

# 이미지(Image)

![HEROPY](https://heropy.blog/css/images/logo.png)  
(링크와 같지만 대괄호밖 맨앞에 !추가)
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/css/images/logo.png)  
(위와 동일하게 대괄호 뒤 소괄호에는 링크추가 대괄호안에는 기존 이미지 넣은방식 모두 복사후 붙여넣음 그러면 이미지 클릭시 링크로이동)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어 사전)
> (>로를 문장 앞에 추가)  
> 인용문
>
> > 인용문
> >
> > > 인용문
> > >
> > > > 인용문  
> > > > (>>>갯수로 인용문 중첩가능)

# 인라인(Inline) 코드 강조

css에서 `background` 혹은
`background-image` 속성으로 요소에 배경이미지를 삽입할 수 있다.  
(백틱기호 즉 그레이브 기호로 앞뒤로 감싸준다.)

# 블록(block) 코드 강조

<a href="http://naver.com">네이버</a>  
이 에이테그를 코드로 보여주고싶으면 백틱 기호를 세번넣고 html쓴뒤 엔터두번후 백틱기호 세번 넣고 그사이에 코드를 삽입

```html
<a href="http://naver.com">네이버</a>
```

```css
a {
  color: red;
}
```

```bash
git init
```

(터미널은 bash라고 해준다)

```plaintext
동해물과 백두산이 마르고 닳도록
하나님이 보우하사 우리나라 만세
```

(텍스트는 plaintext라고 해준다)

# 표(Table)

position 속성

| 값       |       의미       | 기본값 |
| :------- | :--------------: | -----: |
| static   |    기준 없음     |      O |
| relative |    요소 자신     |      X |
| absolute | 위치상 부모 요소 |      X |
| fixed    |      뷰포트      |      X |

(버티컬 바와 띄워쓰기 -하이푼기호 두번 버티컬바 띄워쓰기로 표현)  
:콜론기호를 하이푼 앞뒤로 어디다가 붙이는지에 따라 양쪽이면 가운데정렬 뒤쪽이면 우측정렬 가능

# 원시 HTML(Raw HTML)

동해물과 <u>백두산이</u> <span style="color: blue;">마르고</span> 닳도록  
<b>하나님이</b> 보우하사 우리나라 만세<br/>
(마크다운안에서 html태그 사용)
(이미지 크기나 타겟속성같은것들에 사용)  
<img width="50" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

```html
<img width="50" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />
```

# 수평선(Horizontal Rule)

---

(하이푼 기호 세번)

---

(별표시 세번)

---

(언더바 세번)
