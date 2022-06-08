# cocoa_talk_2022

This is KakaoTalk clone coding.

코코아톡 클론 코딩 2022년 5월 18일 시작!

# 2.2 Our First HTML Tag

-HTML tag 기본-

1. HTML tag 사이에 넣는 텍스트가 무언가가 된다 (title, image, 등등)
2. 브라우저는 아무의미가 없어도 이해하려한다
3. h1 = header no.1, h2 = header no.2 . . . h6까지 존재
4. 브라우저는 내가 임의로 만든 태그를 사용하지 못한다 (텍스트로 표현할 수는 있지만 원하는대로 작동은 안됨)

# 2.3 More Tags and Prettier

-list-

1. orderded list = 순서가 있는 리스트
2. unordered list = 순서가 없는 리스트 (ul)
3. 리스트 안에 사용할 수 있는 태그 = list item (li)

# 2.4 Tag Attributes

a = anchor를 뜻함 (link를 떠올리면 됨) (추가적인 정보가 필요함)
attributes = 태그에 추가하는 정보
href = http reference라고 함 (anchor 태그에만 추가 가능)
target = 기본값은 self이고, "\_blank"(언더바 blank) 입력 시 새 탭에서 링크가 열림
img = 다른 태그와 다르게 /로 닫는 태그가 없다 (자체 닫기 태그이기 때문)
src = img 안에 사진을 집어넣음 (img에서 작동)

# 2.5, 2.6 Head

meta tag = 부가적인 요소 라는 뜻 (content, name attribute를 가짐)
charset = 한글 등 문자 표시하게 해줌
language = 사이트에 사용되는 언어 표기 (검색엔진에게 알려줌)
다른 수많은 meta tag들이 있음
HEAD 태그는 보이지 않는 사이트 설정들을 바꿔준다!! (중요)
og, fb, twitter:~~ 네이버 카카오톡, ~~ 페이스북, ~~ 트위터에서 사용하는 정보들

# 2.7 More Tags

html tag mdn 참고
https://developer.mozilla.org/ko/docs/Web/HTML/Element

# 2.8 Form Tags

요약
form 만들기
input tag = 입력창 만드는 태그
form tag 설명 (기억 못해도 찾아서 사용할 수 있으면 가능)
HTML 문법 형식만 알아두기

# 2.9 More Tags and IDs

lable은 input과 함께 작동한다. (label이 input을 activate)
lable 태그에 for=""
input 태그에 id="" 에 완전 똑같은 벨류가 들어가야 함.

(커서 동시 선택하고 싶을 때는, option 키)

\*핵심은 Id
id는 body 안에 어떤 태그에든 넣을 수 있는 attribute임
element당 하나의 id 만을 가질 수 있다 (고유식별자임, 중복된 id를 사용하면 doesn't work!)
CSS가 태그를 지정하여 꾸미기 위해서 ID가 필요

# 2.10 Semantic HTML

Semantic HTML(document와 code를 명확하게 할 수 있도록 짜는게 좋다)
div tag = division (박스라고 생각해도 됨) 아무런 값이 없는 단순한 box
header tag = 말 그대로 header. div 대체 태그
main tag = 내용을 의미하는 태그. div 대체 태그
footer tag = 꼬릿말을 의미하는 태그. div 대체 태그
span tag= 짧은 텍스트를 의미하는 태그

# 2.11 Recap

-form 은 데이터를 수집하는 컨트롤러
-input의 (고유 식별자)id와 label의 for은 같아야 한다.
-MDN에 사용하는 법 그때그때 잘 찾아보기.
-none-semantic : html에서 의미 없는 태그 but 기능은 있음. (div)
-semantic : 문서를 보기만해도 그 의미를 짐작할 수 있는 것.
(header,main,footer 등)
-> semantic tag를 div나 span으로 바꿔도 문제없지만, 코드 자체를 이해하는데 어려움이 생김.
-p : 문단 텍스트(paragraph)에 적합
-span : 짧은 텍스트에 적합
-div : 한 줄을 띄어준다. box 개념.
결론 :
코드를 이해하기 쉽게하기 위해서 되도록 semantic 태그를 쓰자

- atrribute 값은 항상 "" 큰 따옴표 안에 작성한다.
- 어떤 태그는 id라는 arrtribute를 가질 수 있다.ex) image, paragraph. header, link...
- 반대로 src(source)라는 attribute는 모든 태그가 가질 수 있지 않다.
- 코드 자체에 의미가 부여된 semantic 태그를 잊지 말자.ex) header, navigation, footer...
- semantic 태그로 코드를 작성 하는 것은 매우 중요하다. 작성된 코드들이 훨씬 더 보기 좋고, 좋은
  프로그래머가 되기 위해서는 필수 사항이다.
- header, main, footer, navigation, hgroup 등 <>속 태그들은 전부 container이다. 전부 div 태그로 대체 할 수 있다.
- div 태그는 가장 통용적인 container이다. 대체가 가능하지만, 코드만 보고 어떤 의미인지 파악하기 위해서 semantic 태그를 쓰는 것이다.
- 모든 태그를 암기 할 필요는 없다. 필요할 때마다 문서를 찾아 적용하면 된다.

html element reference MDN 검색

# CSS

## 3.0 How to Add CSS to HTML

- CSS를 HTML과 섞어내는 방법은 두 가지가 있다.
- 1. 같은 HTML 파일에 HTML 코드와 CSS 코드를 놓는 방법
- 2. CSS와 HTML을 분리시키는 방법
- 같은 HTML 파일에 CSS 코드를 입히는 방법으로는 'style'태그를 이용한다.(이 때, head 안에 있어야 한다.)
- CSS를 분리시켜 만들 때는 따로 CSS 파일을 만든다.ex) styles.css
- HTML 파일에서 'link' 태그를 이용하여 CSS 파일과 연결한다.
-
- styles.css와 이 HTML과의 관계를 말할 때, styles.css는 스타일시트라 한다.
- rel(relationship 관계)에 대해 명시해야 한다.

## 3.1 Writing My First CSS Lines

- CSS가 하는 일은 HTML 태그를 가리키는 일. (이 태그는 초록색이다. 이 가리키는 것 자체를 'selector'
- CSS 작성에선 띄어쓰기를 하지 않는다.
- font-size:20px; 과 같이, 속성 다음 콜론(:), 값 다음 세미콜론(;)으로 닫아줘야 한다.

속성이름:속성값;

- 밑줄(\_) 또는 슬래쉬(/)도 사용해선 안된다.
- css 또한 어떤 값이든 쓸 수 있다. 하지만 속성에 맞는 값을 써야 브라우저에서 적용이 된다.
- css 또한 모든 속성을 일일이 다 기억할 필요 없다. 기본적으로 어떻게 동작하는지만 기억하면 된다.

동작 원리

1. 태그를 지정
2. 원하는 속성값을 쓴다.

## 3.2 What Does Cascading Mean

CSS : Cascading Style Sheet

Cascading : 위에서 아래로 내려오는 이미지(폭포가 흐르는 것 떠올리기)

어떤 것 다음에 어떤 것이 온다 이것이 cascading이 의미하는 바다.

브라우저가 CSS 코드를 읽을 때 cascading 방식으로, 즉 위에 있는 코드부터 차례차례로 읽힌다.

위에서 아래로 읽는다는 브라우저가 CSS를 읽는 방법을 아는게 가끔 유용하다.

inline CSS와 external CSS 두 CSS 코드가 같은 대상을 가리키게 되면 어떻게 될까?

→ 브라우저는 위에서 아래로 코드를 읽으므로 마지막에 있는 코드가 우리에게 보여지게 된다.

가장 마지막으로 변경된 속성이 우리에게 보여진다.

그래서 코드의 순서를 바꾸면 최종적으로 보여지는 모습이 달라진다.

CSS는 위에서 아래로 작동한다. 결국 적용 되는 건 가장 마지막 코드다.

## 3.3 Blocks and Inlines

Block과 Inline에 대해 다루어 보았다.

Block은 옆에 다른 요소가 올 수 없는 종류를 뜻하고,

Inline은 옆에 다른 요소가 올 수 있는 종류이다.

Inline은 대채적으로 (span, link, image)이렇게 3종류가 있고 그 외에는 거의다 block 으로 존재한다고 볼 수 있다.

## 3.4 Margin Part One

Block의 특징(margin, padding, border)

block에서 inline으로 inline에서 block으로 바꾸는게 가능할까? → 가능하다

이렇게 하는 걸 display 속성이라고 한다.

기본적으로 span의 display 속성은 inline이다. 이걸 block으로 바꿔주면 span도 block이 된다.

그렇다면 div를 inline으로 바꾸면 어떤 일이 일어날까? → div가 사라진다.

이유는 어떤 요소가 inline이면 그 요소는 높이와 너비를 가질 수 없기 때문이다.

높이와 너비가 없고 내용도 없기 때문에 사라져 보인다. 내용이 있으면 그 내용만큼의 크기를 가지고 보여지게 된다.

inline은 높이와 너비가 없고, block은 높이와 너비가 있다.

block의 엄청난 특징 3가지는 다음과 같다.

브라우저는 요소들에게 원치 않아도 많은 style 속성을 준다.

user agent stylesheet : 브라우저가 기본적으로 준 style 속성

1. margin : block의 border의 바깥에 있는 공간
2. padding : block의 border 안쪽에 있는 공간
3. border : block의 경계

## 3.5 Margin Part Two

방향 설정 없이 margin 하나를 주면 사방에 전부 다 적용된다.
두 개를 줄 경우 상하, 좌우 이다.
네 개를 줄 경우 시계방향 순으로 적용된다. (상 우 하 좌)

Collapsing margin 현상 (상하에서만 발생함)
=> body안에 div의 위 아래 마진이 body의 마진과 만나면 둘 중 큰 값의 마진으로 body에 적용된다.

## 3.6 Padding and IDs

- padding은 block의 경계(border)로부터 '안쪽'에 있는 공간이다.

- 값의 개수에 따라 적용되는 방향은 margin과 동일하다.

- 여러 div를 생성했을 때 'id'를 이용하여 div들을 구분할 수 있고, 각각 다른 속성을 적용시킬 수 있다.

- CSS로 id:first인 div에 속성을 적용 시킬 땐, #first {}

- CSS 코드의 id명은 HTML 코드에서 썼던 id명과 같아야 한다.

## 3.7 Border

- border는 보통 한 종류만 사용한다.

- 적용 예시 → border: 2px solid black; 너비, 스타일, 색깔

- '\*'는 '전체'를 뜻한다.

- border은 inline과 block 모두에 적용된다.

## 3.8 Classes

- span은 inline이기 때문에 높이와 너비를 가질 수 없으며, 그래서 위, 아래에 margin을 가질 수 없다.

- 하지만 padding은 사방에 가질 수 있다.

- 이와 같은 상황에 margin을 위, 아래에 적용하고 싶다면, inline 요소를 block으로 바꿔줘야 한다.

- 온점(.)은 class명이라는 뜻.

- id⇒ #tomato는 id="tomato" class⇒ .tomato는 class="tomato"

- id명과 다르게 class명은 유일할 필요가 없다. 여러 요소들이 같이 쓸 수 있다.

- class="btn tomato"와 같이 class 속에는 btn과 tomato를 연이어 넣어 각각 다른 class 속성을 동시에 부여할 수도 있다.

## 3.9 inline Block

inline-block은 block이 inline 속성을 가지게 해줌
즉, 옆에 둘 수 있고, width와 height를 가질 수 있다.
하지만 문제점이 많다. 정해진 형식이 없음. 그렇기 때문에 잘 안 쓴다.
block 사이에 공간이 제멋대로 생김. => 깔끔하지 못하다.
inline-block은 반응형 디자인을 지원하지 않는다.
즉, 모니터의 크기에 따라 표현이 달라진다.

## 3.10 Flexbox Part One

1. 자식에게 명시하지 않고 부모에게 명시한다.
   ex) div의 부모를 display:flex로 만든다.
2. main axis=> 주축은 (수평)이 기본, justify-content는 main axis를 따라 움직임
3. cross axis=> 교차축은 (수직)이 기본, align-items는 cross axis를 따라 움직임
4. body가 height 값을 갖고있지 않으면 이미 맨 위아래를 차지하고 중심에 있으니까 align-items를 설정하더라도 바뀌지 않음.
   이 때 height를 px로 해도 작동하지만, vh를 사용하면 화면 크기에 따라 바뀐다. 아이폰 맥북 아이패드에 따라 다 달라지니까 유용하다.

## 3.11 Flexbox Part Two

- justify-content나 align-items의 default를 변경하기 위해선, 'flex-direction'을 수정하면 된다.
- flex-direction에는 두 가지 속성, column과 row가 있다.
- display를 flex로 했을 때 default는 row이다. 따라서 flex-direction: column;을 주면 주축과 교차축이 반전된다.
- 원하는만큼 flex 부모-자식 엘리먼트를 만들어낼 수 있다.
- flex-wrap: nowrap;을 통해 wrapping이 일어나지 않게 할 수 있다.
- flexbox는 width값을 초기 사이즈로만 여기고, 모든 엘리먼트를 같은 줄에 있게 하기 위해 width를 바꾸기도 한다.
- flex-direction: column-reverse; 밑에서 시작해서 위로 올라가게 한다.(마찬가지로 row-reverse도 있다.)
- flex-wrap: wrap-reverse; 또한 있는데, 브라우저를 줄일 때, 엘리먼트가 겹쳐지는 위치가 역전된다.

## 3.12 Fixed

position fixed를 이용하면 스크롤해도 항상 제자리에 머무른다.
처음 만들어진 자리에 고정 되어있다. 하지만 top, left, right, bottom 중 하나만 수정해도 서로 다른 레이어에 위치하게되어 원래 위치가 무시된다.
positon fixed를 이용하면 가장 위에 위치하게 된다. (맨 앞)

## 3.13 Relative Absolute

1. position: static (default) - 박스를 처음 위치한 곳에 두는 것
2. position: fixed - 처음에 위치한 자리에서 화면의 스크롤에 상관없이 고정되는 것, top,bottom, left, right 속성을 줘서 고정된 위치 이동시킬 수 있음. 단 이동이 되면 가장 위의 새 레이어에 놓이게됨
3. position : relative - 박스가 처음 위치한 곳을 기준으로 이동,
   top,bottom, left, right 속성을 주면 첫 위치를 기준으로 이동됨
4. position : absolute - 가장 가까운 부모 엘리먼트에 position:relative를 추가한다면, 그 부모 기준으로 top,bottom,left,right이동하고/ 아닐시엔 body 기준으로 이동된다
