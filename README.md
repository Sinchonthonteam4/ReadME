# ReadME
2023 신촌톤의 organization을 위한 리드미 양식입니다.
---

# 서비스명 Cafeiner

<div align="center">
<img width="329" alt="image" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/bfa67065-c11b-4961-a1b5-3b27cb7e873d">
</div>

# 2023th Sinchonthon
> **신촌톤 커피 마스터팀** <br/>

## 배포 주소

> 웹페이지 주소 어쩌구 저쩌구 <br>

## 팀 소개

|       주한아 <br/> **(기획/디자인)**       |          서가영 <br/> **(개발/프론트엔드)**          |       장세환 <br/> **(개발/프론트엔드)**        |       진규빈  <br/> **(개발/프론트엔드)**       |       김유이  <br/> **(개발/백엔드)**       |       김희선  <br/> **(개발/백엔드)**       |       이상민  <br/> **(개발/백엔드)**       |                                                                                                     
| :------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------: |  :---------------------------------------------------------------------------------------------------------------------------------------------------: |  :---------------------------------------------------------------------------------------------------------------------------------------------------: |  :---------------------------------------------------------------------------------------------------------------------------------------------------: |
|   <img width="160px" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/5e1d7e98-b9d2-4deb-a4b6-b94a04267cef" />    |                      <img width="160px" src="https://avatars.githubusercontent.com/u/102040717?v=4" />    |                   <img width="160px" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/c205c52a-c1e6-4f6b-8058-e7b4dd9afd80"/>   |   <img width="160px" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/a91706e5-36e8-418e-92b3-6c9abb3dfa7c" />    |   <img width="160px" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/a91706e5-36e8-418e-92b3-6c9abb3dfa7c" />    |   <img width="160px" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/a91706e5-36e8-418e-92b3-6c9abb3dfa7c" />    |
|   [zhivago-kim](https://www.linkedin.com/in/zhivago-kim)   |    [529539](https://github.com/529539)  |    [THLcode](https://github.com/THLcode)  |    [@wooseok123](https://github.com/wooseok123)  |
| 홍익대학교 경영학  | 홍익대 컴퓨터공학 | 서강대 컴퓨터공학 | 이화여대 생명공학 | 서강대 국어국문학 | 연세대 컴퓨터과학 | 홍익대 컴퓨터공학 |

## 프로젝트 소개


**카페이너**는 과다한 카페인 섭취로 건강에 악영향을 겪고 있는 대학생들을 위한 서비스입니다. 대학생의 소비 형태에 맞춰진 간편 기록을 통해 자신의 카페인 섭취 습관을 확인할 수 있고, 그룹형 챌린지 시스템을 통해 헬시 플레저를 추구합니다.

#### 카페이너, 카페인 수혈에 찌든 대학생을 위한 참여형 습관 개선 서비스
대학생이 주로 소비하는 프랜차이즈 카페와 편의점의 음료 정보가 연동되어 있어 자신의 카페인 섭취량을 쉽게 기록할 수 있어요.
카페인 섭취량의 추이를 시각적으로 확인할 수 있어요.
각 대학에 속한 학생들의 기록을 모아 학교별로 경쟁하며 즐겁게 건강을 관리할 수 있어요.

#### 카페이너, 간단한 사용과 편리함 (스텝별 사용자가 해야하는 것 어필~).

1. 회원가입 후 로그인해 주세요.
2. 브랜드명과 메뉴를 선택하여 간편하게 하루 동안 섭취한 카페인을 기록하세요.
3. 각자가 작성한 기록으로 주간 결과 레포트를 확인하거나, 우리 학교의 카페인 섭취량 순위를 파악할 수 있어요.

## 시작 가이드
### 필수사항
해당 어플리케이션을 동작하기 위해선 다음 버전 이상이 필요해요.

- [Node.js 14.19.3](https://nodejs.org/ca/blog/release/v14.19.3/)
- [Npm 9.2.0](https://www.npmjs.com/package/npm/v/9.2.0)
- [Python 3.11.4](https://www.python.org/downloads/release/python-3114/)

### Installation
``` bash
$ git clone git@github.com:wooseok123/sinchonthon_readme.git
$ cd 프로젝트명
```






(모노레포인 경우)
#### Backend
```
$ cd server
$ mkdir .venv
$ pipenv install
$ source .venv/Scripts/activate
$ python3 manage.py makemigrations
$ python3 manage.py migrate --run-syncdb
$ python3 manage.py init_univs
$ python3 manage.py init_starbucks
$ python3 manage.py runserver
```

#### Frontend
```
$ cd front
$ npm install 
$ npm run dev
```

---

## Stacks 🐈

### Environment
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)             

### Config
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)        

### Development
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white)

### Communication
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)

---
## 화면 구성 📺
| **메인 페이지**  |  **서비스 페이지 1**   |
| :-------------------------------------------: | :------------: |
|  <img width="329" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/a40b9b11-3833-4b81-8dea-9e34b10f81a7"/> |  <img width="329" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/a40b9b11-3833-4b81-8dea-9e34b10f81a7"/>|  
| **서비스 페이지 2**   |  **서비스 페이지 3**   |  
| <img width="329" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/a40b9b11-3833-4b81-8dea-9e34b10f81a7"/>   |  <img width="329" src="https://github.com/wooseok123/sinchonthon_readme/assets/59460718/a40b9b11-3833-4b81-8dea-9e34b10f81a7"/>     |

---
## 주요 기능 📦

### ⭐️ 카페인 섭취량 기록 기능
- 프랜차이즈의 메뉴 데이터베이스를 이용한 간편 기록 기능

### ⭐️ 기록 확인 기능
- 하루의 카페인 섭취량을 시각화한 인터페이스 제공
- 일주일의 기록을 확인할 수 있는 주간 결과 레포트 제공

### ⭐️ 챌린지 참여 기능
- 대학별 카페인 섭취량 기록 순위 경쟁 시스템

---
## 아키텍쳐

### 디렉토리 구조
```bash
├── README.md
├── SERVER : 백엔드
│   ├── Pipfile
│   ├── requirements.txt
│   ├── manage.py
│   ├── accounts : 사용자 계정 관리
│   │   ├── urls.py
│   │   ├── views.py
│   │   ├── etc..
│   ├── cafes : 프랜차이즈 카페와 음료 정보
│   │   ├── urls.py
│   │   ├── views.py
│   │   ├── etc..
│   ├── challenge : 대학별 챌린지 기능
│   │   ├── urls.py
│   │   ├── views.py
│   │   ├── etc..
│   ├── reports : 카페인 섭취량 기록 기능
│   │   ├── urls.py
│   │   ├── views.py
│   │   ├── etc..
│   ├── config
│   │   └── settings.py
│   │   └── urls.py
│   ├── static
│   │   └── admin
│   │   └── rest_framework
└── Frontend : 프론트엔드
    ├── README.md
    ├── public
    │   ├── favicon.ico
    │   └── logo_about.png
    ├── components
    │   ├── a.js : 필요시 설명~
    │   ├── b.js
    │   ├── c.js
    │   ├── d.js
    │   ├── e.js
    │   ├── f.js
    │   ├── g.js
    │   ├── h.js
    │   └── i.js
    ├── package-lock.json
    ├── package.json
    ├── pages
    │   ├── page1.js
    │   ├── page2.js
    │   ├── page3.js
    │   ├── page4.js
    │   ├── newcourse
    ├── app.js
    ├── index.js
    ├── router.js
    └── styles
        └── GlobalStyle.js

```

<!--
```bash
├── README.md : 리드미 파일
│
├── strapi-backend/ : 백엔드
│   ├── api/ : db model, api 관련 정보 폴더
│   │   └── [table 이름] : database table 별로 분리되는 api 폴더 (table 구조, 해당 table 관련 api 정보 저장)
│   │       ├── Config/routes.json : api 설정 파일 (api request에 따른 handler 지정)
│   │       ├── Controllers/ [table 이름].js : api controller 커스텀 파일
│   │       ├── Models : db model 관련 정보 폴더
│   │       │   ├── [table 이름].js : (사용 X) api 커스텀 파일
│   │       │   └── [table 이름].settings.json : model 정보 파일 (field 정보)
│   │       └─── Services/ course.js : (사용 X) api 커스텀 파일
│   │ 
│   ├── config/ : 서버, 데이터베이스 관련 정보 폴더
│   │   ├── Env/production : 배포 환경(NODE_ENV = production) 일 때 설정 정보 폴더
│   │   │   └── database.js : production 환경에서 database 설정 파일
│   │   ├── Functions : 프로젝트에서 실행되는 함수 관련 정보 폴더
│   │   │   │   ├── responses : (사용 X) 커스텀한 응답 저장 폴더
│   │   │   │   ├── bootstrap.js : 어플리케이션 시작 시 실행되는 코드 파일
│   │   │   │   └── cron.js : (사용 X) cron task 관련 파일
│   │   ├── database.js : 기본 개발 환경(NODE_ENV = development)에서 database 설정 파일
│   │   └── server.js : 서버 설정 정보 파일
│   │  
│   ├── extensions/
│   │   └── users-permissions/config/ : 권한 정보
│   │ 
│   └── public/
│       └── uploads/ : 강의 별 사진
│
└── voluntain-app/ : 프론트엔드
    ├── components/
    │   ├── NavigationBar.js : 네비게이션 바 컴포넌트, _app.js에서 공통으로 전체 페이지에 포함됨.
    │   ├── MainBanner.js : 메인 페이지에 있는 남색 배너 컴포넌트, 커뮤니티 이름과 슬로건을 포함.
    │   ├── RecentLecture.js : 사용자가 시청 정보(쿠키)에 따라, 현재/다음 강의를 나타내는 컴포넌트 [호출: MainCookieCard]
    │   ├── MainCookieCard.js : 상위 RecentLecture 컴포넌트에서 전달받은 props를 나타내는 레이아웃 컴포넌트.
    │   ├── MainCard.js : 현재 등록된 course 정보를 백엔드에서 받아서 카드로 나타내는 컴포넌트 [호출: CourseCard]
    │   └── CourseCard.js : 상위 MainCard 컴포넌트에서 전달받은 props를 나타내는 레이아웃 컴포넌트
    │
    ├── config/
    │   └── next.config.js
    │
    ├── lib/
    │   └── ga/
    │   │   └── index.js
    │   └── context.js
    │
    ├── pages/
    │   ├── courses/
    │   │   └── [id].js : 강의 페이지
    │   ├── _app.js : Next.js에서 전체 컴포넌트 구조를 결정, 공통 컴포넌트(navbar, footer)가 선언되도록 customizing 됨.
    │   ├── _document.js : Next.js에서 전체 html 문서의 구조를 결정, lang 속성과 meta tag가 customizing 됨.
    │   ├── about.js : 단체 소개 페이지
    │   ├── index.js : 메인 페이지
    │   ├── question.js : Q&A 페이지
    │   └── setting.js : 쿠키, 구글 애널리틱스 정보 수집 정책 페이지
    │
    ├── public/
    │   ├── favicon.ico : 네비게이션바 이미지
    │   └── logo_about.png : about 페이지 로고 이미지
    │
    └── styles/
        └── Home.module.css

```
-->
