# 제목(Header)
<!-- # 개수로 제목 설정 -->
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장 (Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Braaks)
<!-- 띄어쓰기 2번이나 br 태그 사용 -->
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br />  
대한 사람 대한으로 길이 보전하세

# 강조 (Emphasis)

_이탤릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
<!-- 물결표시 두개~~취소할 문장~~ -->
~~취소선~~   
<u>밑줄</u>

# 목록(List)
<!-- 들여쓰기 2번 -->
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록  
    1. 순서가 필요한 목록
1. 순서가 필요한 목록
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

# 링크 (link)
  <a herf="https://google.com">GOOGLE</a>

  [GOOGLE](https://google.com)

  <a herf="https://naver.com" target="_blank">NAVER</a>

  [NAVER](https://naver.com "NAVER로 이동!")


  # 이미지 (image)

  <!-- ![]() -->

  ![EYON](https://raw.githubusercontent.com/ParkYoungWoong/starbucks-vanilla-app/master/favicon.png)

  [![EYON](https://image-cdn.hypb.st/https%3A%2F%2Fkr.hypebeast.com%2Ffiles%2F2022%2F09%2Frumors-that-supreme-registered-trademark-rights-in-korea-ft.jpg?w=960&cbr=1&q=90&fit=max)](https://naver.com)

  
  # 인용문(BlockQuote)
  > 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
  > (네이버 국어 사전)
  > 인용문을 작성하세요!
  >> 중첩된 인용문
  >>> 중첩된 인용문 1  
  >>> 중첩된 인용문 2  
  >>> 중첩된 인용문 3


  # 인라인(inline) 코드 강조

  CSS에서 `background` 혹은   
  `background-image` 속성으로 요소에   
  배경 이미지를 삽입할 수 있습니다.


  # 블록코드(block) 코드 강조

```html
<a herf="https://naver.com" target="_blank">NAVER</a> 
```

```css
.list li {
  background-color
}
```

```bash
$ git commit -m 'study markdown'
# 여기서 $는 터미널에 입력한다는 표시이다. 실제로는 입력하지 않는다. 궁금증 해결!
```

```javascript
function func(){
  var a = 'AAA';
  return a;
}
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```
---
# 표 (table)

position 속성

값 | 의미 | 기본값
-- | :--: | --:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

---    



# 원시 HTML (Raw HTML)

동해물과 <u>백두산이</u> 마르고 닳도록  
하느님이 보우하사 우리나라 만세

동해물고 <span style="text-decoration:underline;">백두산</span>이 마르고 닳도록  
하느님이 보우하사 우리나라 만세

<a href="https://google.com" target="_blank">GOOGLE</a>  
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)

---

***

___
