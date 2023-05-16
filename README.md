# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리하나 만세

# 줄바꿈(Line Breaks) - 띄어쓰기 두번 & br태그

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리하나 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 체크박스

- [x] 수동 과 자동 선택 가능 o
- [x] 통계구현 o
- [x] 수익 구현 o
- [x] 프로그램 종료되지 않도록 구현 o
- [ ] 보너스 번호 구현 x
- [x] 수동, 자동 오름차순 정렬 o
- [x] 수동, 자동 중복 해결o
- [x] 예외처리 o
- [ ] 예외처리 재검토 및 분리 에정
- [ ] 수익률 해석 추가 예정
- [ ] MVC분리중 (예정)

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지(Images)

![]()

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/) -- 이미지 누르면 해당 사이트로 이동

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3

# 인라인(Inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경이미지를 삽입할 수 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리하나 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본 값  
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

<span style="text-decoration: underline">동해물</span>과 <u>백두산이</u> 마르고 닳도록<br/>
하느님이 보우하사 우리하나 만세

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***

___
