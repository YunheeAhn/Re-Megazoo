# Re-Megazoo
Megazoo website Renewel with responsive Web

2023-12-14
:start index.html - mobile main page(only html)
:start css - mobile main page

2023-12-15
:header - comm.css
:add image(not included comm.css)

2023-12-17
:슬라이드 텍스트
:메인 배너 이미지 스와이퍼

2023-12-18
:gnb hover 안되는 오류 수정
:슬라이드 텍스트 span 태그 안 텍스트 해결 완료

2023-12-19
: :root변수 설정
: 올메뉴 호버했을때 메인배너 스와이퍼 뒤로 숨고, 슬라이드 텍스트 위로 올라오는 에러 발생
    -> allmenu에 z-index설정
: #sec-bg 배경 이미지 안 입혀지는 오류 발생
    -> 백그라운드 이미지 요소 아닌 백그라운드로 설정
=>오류 해결

2023-12-20
: #main>.sec02~04 밀림 현상 해결
    -> transform : translateX(-10px)
