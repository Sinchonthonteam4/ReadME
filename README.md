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
|   <img width="160px" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/5a789562-8b4f-44bd-bc79-19764e8a418e" />    |                      <img width="160px" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/5a789562-8b4f-44bd-bc79-19764e8a418e" />    |                   <img width="160px" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/5a789562-8b4f-44bd-bc79-19764e8a418e"/>   |   <img width="160px" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/5a789562-8b4f-44bd-bc79-19764e8a418e" />    |   <img width="160px" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/5a789562-8b4f-44bd-bc79-19764e8a418e" />    |   <img width="160px" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/5a789562-8b4f-44bd-bc79-19764e8a418e" />    |   <img width="160px" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/5a789562-8b4f-44bd-bc79-19764e8a418e" />    |
|   [zhivago-kim](https://www.linkedin.com/in/zhivago-kim)   |    [529539](https://github.com/529539)  |    [THLcode](https://github.com/THLcode)  |    [@wooseok123](https://github.com/wooseok123)  |
| 홍익대학교 경영학  | 홍익대 컴퓨터공학 | 서강대 생명공학 | 이화여대 컴퓨터공학 | 서강대 국어국문학 | 연세대 컴퓨터과학 | 홍익대 컴퓨터공학 |

## 프로젝트 소개


**카페이너**는 과다한 카페인 섭취로 건강에 악영향을 겪고 있는 대학생들을 위한 서비스입니다. 대학생의 소비 형태에 맞춰진 간편 기록을 통해 자신의 카페인 섭취 습관을 확인할 수 있고, 그룹형 챌린지 시스템을 통해 헬시 플레저를 추구합니다.

#### 카페이너, 카페인 수혈에 찌든 대학생을 위한 참여형 습관 개선 서비스
대학생이 주로 소비하는 프랜차이즈 카페와 편의점의 음료 정보가 연동되어 있어 자신의 카페인 섭취량을 쉽게 기록할 수 있어요.
카페인 섭취량의 추이를 시각적으로 확인할 수 있어요.
각 대학에 속한 학생들의 기록을 모아 학교별로 경쟁하며 즐겁게 건강을 관리할 수 있어요.

#### 카페이너, 간단한 사용과 편리함

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
$ git clone git@https://github.com/Sinchonthonteam4/Frontend
$ cd 프로젝트명
```






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
|  <img width="329" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/caeff266-3419-4d56-8000-88734c3a0c59"/> |  <img width="329" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/23039bf7-80ac-42d3-8636-d52f49157c1b"/>|  
| **서비스 페이지 2**   |  **서비스 페이지 3**   |  
| <img width="329" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/3b10a71d-11c7-4622-ad1d-91691180d8ff"/>   |  <img width="329" src="https://github.com/Sinchonthonteam4/ReadME/assets/74279249/cae940f0-a67b-45ff-88da-5312cc05e232"/>     |

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
 

```

