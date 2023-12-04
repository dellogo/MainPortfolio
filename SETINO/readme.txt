===페이지 구성===

1. 메인페이지
    -> 로딩화면 FADEIN, FADEOUT
    -> 배경색/오른쪽 index_bar 길이 removeClass,addClass로 바뀌게 setinteval
    -> 마우스 스크롤시 배경색, index_bar길이, item_title, index_num 순차변경
    -> 중앙 item_img 호버시 scale 변경
    -> 화면 너비가 1000px보다 작으면 헤더 메뉴 포지션, 중앙 이미지 크기, text위치, 회전, 크기 변경
    -> collection_nav 호버시 small_ul slidedown
2. 브랜드 소개 페이지
    -> 스크롤 이벤트
	- scroll_top이 mainbanner_top과 같거나 크면 이미지 크기 커짐
	- scroll_top이 (mainbanner_top/2)과 같거나 크면 이미지 크기 커짐
	- scroll_top이 main_banner_bottom과 같거나 크면 이미지 전체화면, img_top = window_top
	- scroll_top이 (img_bottom - 300)과 같거나 크면 left_txt opacity 1로 변경
	- scroll_top이 left_txt_bottom보다 같거나 크면 right_txt poacity 1로 변경 & 배경색 #000으로 변경
	- scroll_top이 right_txt_top보다 같거나 크면 배경색 #e9e6da로 변경
3. 리스트페이지(new, best, scent, bath&body, home fragrance)
    -> 문서 높이가 scroll_top+현재 높이+200 보다 크면 상품 리스트 10개 추가
    -> 스크롤 두번되면 무한스크롤 중지 & footer 나타남
    -> 상품 호버시 scale 커짐 & opacity변경
    -> 상품 클릭하면 상세페이지 이동
4. 상품 상세페이지
    -> 클릭한 해당 상품 정보 불러옴
    -> 수량 증가시 해당 상품 가격 * 구매개수로 최종 구매가격 변경
    -> 이미지 호버시 scale 커짐 & opacity 변경
5. 브랜드 컨택페이지
    -> 페이지 이동시 main opacity 변경 & 아래에서 위로 올라옴
6. 메뉴페이지
    -> 오른쪽 상단 메뉴 버튼 클릭시 메뉴 화면 slideDown, 한번 더 클릭하면 slideUp
    -> 오른쪽 상단 메뉴 버튼 클릭하는 순간의 페이지 글자 기본색 white, 호버시 white
    -> 메뉴 화면의 nav 클릭하면 해당 페이지로 이동
    -> 로그인 클릭시 로그인화면 FadeIn, x버튼 클릭시 Fadeout, password & password_check 불일치시 alert
    -> 로그인화면에서 go_signup 클릭시 login화면 Fade Out, signup 화면 Fade In
    -> 회원가입 클릭시 회원가입화면 FadeIn, x버튼 클릭시 Fadeout, password & password_check 불일치시 alert


===벤치마킹 사이트===
http://batino.co.kr/
https://www.jomalone.co.kr/


===주색===
#e9e6da
#a9a9a9
#fff
#000