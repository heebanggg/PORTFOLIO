# PORTFOLIO
개인 포트폴리오 사이트입니다.


<img width="100%" alt="이름바꿔" src="이미지경로" />

<b>

- 📝 [소개](#-포트폴리오-개요)
- 🛠 [STACK](#-STACK)
- ✨ [팀프로젝트](#-팀프로젝트)
   - 👨🏻‍💻 [코드](#-코드)
   - 👨🏻‍💻 [구현](#6-구현)
- ⏰ [커밋 히스토리](#-커밋-히스토리)

</b>  

## **📝 포트폴리오-개요**

<img width="100%" alt="메인 페이지" src="" />

> **프로젝트:** 개인 포트폴리오 사이트
>
> **기획 및 제작:** 박희범
>
> **분류:** 팀 프로젝트
>
> **제작 기간:** 2023 07.17 ~ 09.13
>
> **주요 기능:** 메인페이지, 상품별 트렌드, 랭킹 미리보기
>
> **사용 기술:** 협업툴: Notion, Google Sheets, Google Slides, Google Drive 개발환경:eclips 프레임워크:spring, MyBatis
>   데이터 베이스: mysql WAS: Apache Tomcat 9.0 버전관리: GitHub, Sourcetree, git 언어: JAVA, JSP, AJAX, HTML5, CSS3
>   라이브러리: jquery, commonsDBCP, Bootstrap

> **문의:** qkrgmlqja90@naver.com

<br />

## **🛠 STACK**
![Spring Framework](https://img.shields.io/badge/SpringFramework-FFFF33?style=flat-square&logo=spring) ![MariaDB](https://img.shields.io/badge/MariaDB-339933.svg?style=flat-square&logo=MariaDB)
![MySQL](https://img.shields.io/badge/MySQL-%23121011.svg?style=flat-square&logo=MySQL) ![HTML5](https://img.shields.io/badge/HTML5-CCCCFF.svg?style=flat-square&logo=HTML5) ![JavaScript](https://img.shields.io/badge/JavaScript-FFCCCC.svg?style=flat-square&logo=JavaScript) 


<br />

## **✨ 팀프로젝트**

- About 섹션에 이력서 및 자기소개서 다운로드 기능 추가(21.10.13)

<br />

## **👨🏻‍💻 기능 구현**

### **1. 메인페이지**


![01 메인페이지 - 복사본](https://github.com/heebanggg/PORTFOLIO/assets/134472331/7faaa8a2-e8e7-4923-a06e-edcc2824d468)

- AI로 요즘 트렌드를 알아볼수있게 메인페이지를 구현했다



### **2. 상품별 트렌드**

![상품별 트렌드 미리보기](https://github.com/heebanggg/PORTFOLIO/assets/134472331/816c8fef-2db6-4d01-b3c9-3a46454a3d73)

- 상품별 트렌드를 한눈에 볼수있게 설정



### **3. 랭킹 미리보기**

![랭킹미리보기](https://github.com/heebanggg/PORTFOLIO/assets/134472331/b543eaa7-9dda-4e9e-98e2-0e4389661f3c)

- DB로 검색기록을 일간, 주간, 월간 순으로 저장 후 검색기록 많은 순서대로 랭킹 1위로 올수있게 설정해두었다



### **4. 상품별 트렌드 미리보기**

![상품별 트렌드 미리보기](https://github.com/heebanggg/PORTFOLIO/assets/134472331/01174e33-f44e-4a70-872d-df1afb8759ac)



### **5. Open graph**

<img width="100%" alt="스크린샷 2021-10-06 15 02 30" src="https://user-images.githubusercontent.com/51189962/136148865-7b6cfd30-ae66-410f-89fa-16f9ad883c74.png" />

<img width="100%" alt="스크린샷 2021-10-06 15 03 15" src="https://user-images.githubusercontent.com/51189962/136148961-28e8c84b-b5fb-4052-9150-7c20e6af3cbc.png" />

```html
<!-- index.html -->
<meta property="og:title" content="김태진 • Frontend Developer" />
<meta property="og:description" content="프론트엔드 개발자 김태진입니다." />
<meta property="og:image" content="%PUBLIC_URL%/thumb.png" />
<meta property="og:url" content="https://keemtj.com/" />
<meta property="og:type" content="website" />
```

- meta tags를 통해 Facebook, twitter, linkedin, discord, kakao talk 등 링크를 전달 했을 때 링크에 대한 정보를 볼 수 있도록 구현
- https://www.opengraph.xyz

### **6. 기타 기능**

- favicon.ico 생성
- Fade-in transform
- 프로젝트 페이지
- React-responsive-carousel 커스텀

## **🚀 배포**

- 첫 배포

```
$ npm install -g firebase-tools
$ firebase init
$ firebase login
  > HOSTING
  > Directroy? build
$ yarn build
$ firebase deploy
```

- 수정 후 배포

```
$ yarn build
$ firebase deploy
```

- 커스텀 도메인: Godaddy에서 커스텀 도매인 구매(https://keemtj.com)

<br />

## ⏰ 커밋 히스토리

[내 커밋 히스토리 보러가기](https://github.com/keemtj/portfolio/commits?author=keemtj)
<br/>
<br/>
<br/>

주요 기술: 라이트/다크 모드, 반응형 웹, Hash Link, Email 전송, 배포 및 커스텀 도메인 연결, open graph

문의: qkrgmlqja90@naver.com

🛠 기술 및 도구
React Styled-Components Firebase GitHub
🔗 링크
링크: https://keemtj.com
✨ 업데이트
About 섹션에 이력서 및 자기소개서 다운로드 기능 추가(21.10.13)
👨🏻‍💻 기능 구현
⏰ 커밋 히스토리
