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
