# AnywhereDoctor

**Project Info**

| 프로젝트 명 | 현대인을 위한 원격진료 플랫폼(애니웨어닥터, AnywhereDoctor) |
| --- | --- |
| 개발 기간 | 2022. 09. 01 ~ 2022. 12. 13 |
| 참여인원 | 4명 |
| 담당업무 | 형상 관리, 엔지니어, App 개발, 챗봇 개발 |

**Use Technology**

| 개발 환경 | Windows, MAC |
| --- | --- |
| 사용 도구 | Android Studio |
| 사용 기술 | JAVA, XML, HTML, CSS, Javascript, Firebase Realtime Database, Firebase Storage, DialogFlow |

**Introduction**

---

내용 요약

- 기존 원격진료 플랫폼의 세 가지 기능(화상 진료, 약 처방 및 배송, )을 포함하는 애니웨어닥터(AnywhereDoctor)
    - 화상 진료 : 언제 어디서나 병원과 의사를 선택하여 진료
    - 약 처방 및 배송 : 진료를 통해 환자 질병에 맞는 약을 처방, 배송받도록 도움
    - 빠른 진료과 찾기 챗봇 : 환자가 진료 전에 진료과를 수월하게 선택하도록 도움
        
        ![스크린샷 2022-12-08 오후 9.20.14.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/db3426d0-cb7d-4dfd-8521-06b69a5d96c7/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2022-12-08_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9.20.14.png)
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fcdb6bcf-21aa-463b-bd24-9581c23ed158/Untitled.png)
        

---

상세 내용 기술

- **Web** : 의사와 약사가 사용하는 AnywhereDoctor 페이지, 관리자가 사용하는 Medistant 페이지로 나누어 개발을 진행하였다. 웹페이지를 만들기 위해 기본적인 Front-End를 HTML, CSS, Javascript, JSP 파일을 작성하고, DB가 필요한 페이지에서 Firebase를 사용해주기 위해 CDN을 html 내에 작성해 주고 본인의 Firebase 프로젝트 주소를 기입한다.
- **App** : 환자가 사용하는 AnywhereDoctor 애플리케이션을 만들기 위해 XML, JAVA 코드를 작성하고, Firebase 실시간 데이터베이스와 스토리지를 활용하여 개발을 진행한다. 로그인 및 결제는 카카오톡, 카카오페이로 진행한다. 챗봇을 생성해 앱 내에서 작동 가능하도록 한다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/746cd292-de84-4919-a197-ab679506d44b/Untitled.png)

---

관련 수상 내역 및 논문

- 2022학년도 캡스톤디자인 경진대회 ‘우수상’
    - 수상일 : 2022년 12월 1일
    - 주최행사 : 3단계 산학연협력 선도대학 육성사업 (LINC 3.0)
    - 주최사 : 건양대학교 LINC 3.0 사업단
- 원격진료 플랫폼 웹페이지와 애플리케이션 개발에 대한 연구(A Study on the Development of Telemedicine Platform Web Pages and Applications)
    - 저자 : 최하늘(Ha-neul Choi), 강병익(Byung-Ik Kang, 담당교수)
    - 작성일 : 2022. 11. ~ 2022. 12.
    - 2022 한국정보기술학회 추계 종합학술대회
