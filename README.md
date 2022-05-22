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
