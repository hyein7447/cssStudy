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