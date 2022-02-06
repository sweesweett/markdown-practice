

# 제목(header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

## 문장(Paragragh)
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라만세

## 줄바꿈(Line Breaks)

줄바꿈 할 때 띄어쓰기 2번을 사용한대  
이렇게 말이야. 근데 그게 안먹히는 경우는  
br태그를 사용하라고 하네? <br />
이렇게 말이야
## 강조(Emphasis)
_이텔릭_ 근데 띄어쓰기는 안된다...  
이렇게 _이텔릭 체로 하고픈 곳은 짝대기 2개 하면 돼_  
_근데 끝날떄 띄어쓰기로 끝나면 인식을 못하지 _  
**두껍게**  
**_이텔릭 + 두껍게_** 이중으로 가능하다  
~~취소선~~
밑줄을 제공하는 기능은 없대  
<u>밑줄</u>

## 목록(List)
1. 순서가 필요한 목록
1. 근데 이걸하면 띄어쓰기를 못하나?  
    1. 이거봐 대단한걸?  
    1. 생각보다 흥미롭다
1. 숫자적고 띄어쓰기를 하고싶은데 못하네 
<ol><li>html에서는 이렇게</li> </ol>

- 순서가 필요하지 않은 목록  
  - 순서가 필요하지 않은 목ㄹ고
- 순서가 필요하지 않은 목록

# 링크(Links)
<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)  

<a href="https:/naver.com" title="NAVER로 이동!">NAVER</a>   
[NAVER](https://naver.com "네이버로 이동!")

마크다운은 target과 같은 속성을 제공하지 않기 때문에  
원시 HTML 즉 순수 HTML을 사용해 작성

# 이미지(Image)
![heropy](https://heropy.blog/css/images/logo.png)  
  
링크와 이미지의 차이는 !느낌표 차이!

[![heropy](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)  
  
이미지에 링크 넣기!
# 인용문(BlockQuote)

>남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어 사전)

>인용문은 중첩내용이있음
>>중첩된 인용문
>>> 이거봐 이렇게  
>>> 중첩하는건가봐  
>>> 중첩3


# 인라인(Inline) 코드 강조
CSS에서 `background` 혹은 background-image 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.
# 블록(block) 코드 강조


```html
<a href ="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```
오 신기하다 
```javascript
functio func(){
  var a ='aaa'
  return a;
}
```
# 표(Table)
position 속성

값 | 의미 | 기본값  
--|:--:|--:  
static | 기준 없음 | O  
relative | 요소 자신 | X 
absolute | 위치 상 부모 요소  | X  
fixed | 뷰포트 | X   
**왼쪽 정렬(기본값)**| **가운데 정렬** | **오른쪽 정렬**
# 원시 HTML (Raw HTML)
동해물과 <span style="text-decoration:underline;">백두산이</span> 마르고 닳도록 <br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="네이버로 이동!" target="_blank">NAVER</a>  
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선(Horizontal Rule)
---  

***  
___