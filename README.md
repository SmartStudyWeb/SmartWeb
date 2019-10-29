# Smart Study Calendar
학부 공지, 시간표, 개인 일정, 노트필기, 수업녹음을 한번에

http://www.smart-study-calendar.com

http://smart-study-calendar.herokuapp.com

오픈소스 소프트웨어 5조 1차 프로젝트

# 기능
![서비스소개_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.05.41.png)


## 회원서비스
![로그인_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.06.06.png)
OAuth를 이용한 소셜 계정 로그인


## 노트 필기
![나의캘린더_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.08.39.png)
유저 개인 캘린더 페이지

![다이어리_작성_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.27.23.png)
각 이벤트 일정, 즉 각 과목별로 필기를 작성


## 캘린더
![이벤트_추가_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.29.38.png)
시간표 이벤트 외에 개별 일정들을 등록


## 학사시간표 자동 등록
![에브리타임_시간표_연동_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.08.05.png)
/connect-everytime
에브리타임 서비스의 시간표 URL공유 기능을 이용하여 사용자의 시간표를 연동

![에브리타임_시간표_연동_확인_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.08.29.png)
/connect-everytime/check
서버에서 시간표를 처리한 결과를 표시

![에브리타임_시간표_연동_확인_페이지_오류](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.44.55.png)
/connect-everytime/check
기본적으로 프론트엔드에서 input type을 url로 지정하여 텍스트박스에 입력한정보가 URL이고 minlength와 required를 충족했는지 확인하고 백엔드에서 도메인이 에브리타임서비스인지 확인하여 시간표를 처리합니다.

## 공지 자동 스크랩
![공지_캘린더_페이지](./Docs/IMAGES/스크린샷%202019-10-29%20오전%2010.28.05.png)
공지를 서버에서 RSS를 기반으로 스크랩하여 캘린더형태로 구성

# 조원
5조
 - 20153163 김정환 [@JasonKJ](https://github.com/JasonKJ)
 - 20171598 김예지 [@kookminYeji](https://github.com/kookminYeji)
 - 20181616 박정섭 [@ParkJeongseop](https://github.com/ParkJeongseop)
