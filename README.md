# CSS Style Sheet
----
## CSS 작성위치
* 내부스타일시트 `<head><style>여기 작성</style></head>`
* 외부스타일시트 styles/파일명.css 별도 생성 후
    `<link rel="stylesheet" href="./styles/파일명.css">`
----
## font-family 글꼴 설정
*  `선택자 {font-family:'대표글꼴', '보조글꼴'}`
* 모든 사용자에게 동일한 글꼴을 보여줄 수 있도록 웹 글꼴을 사용하는 것이 좋다!
fonts.google.com 추천
----
## font-size 글자크기
* 웹브라우저 평균 글자크기는 16px(100%)이다.
* px은 절대크기이므로 모바일 디바이스에 적합하지 않아 em 또는 rem 단위를 사용한다 (%가능)
* `선택자 {font-size:1.0em;}`
* `선택자 {font-size:1.0rem;}`
* `선택자 {font-size:100%;}`
* 글자크기값은 부모에 상속받게 하지 않고 적용 대상 자체한테 작성하는 것이 좋다!
(이유 : 부모한테 줄 경우 우선순위에 가로 막혀서 적용안됨.)
* ★★개발자도구 (F12) 우선순위 css를 자주 확인해야함 !! ★★
----
## color 글자 색상
* 글자색상은 단순 테스트 용도로 사용할때는 영문으로 사용한다. ex)aqua,blue
* 실제 디자인 용도로 사용할 때는 rgba, #헥사코드 6자리, 3자리를 사용한다.
* `선택자 {color:#ff0000;}`
* `선택자 {color:rgba(255,0,0,0.5)}`
----
## line-height 행간
* 행간 값은 1.0(100%) 또는 50px 방식으로 작성한다.
* `본문 12~18px 내용 글자 크기 기준 1.3~1.7 값을 많이 사용한다. (평균 1.5)`
* 제목 글자의 경우 글자크기에 따라 행간값은 상대적으로 다르기 때문에 자주 체크하며 수정해야 한다.
----