# ☁ NINE Cloud

## ✍🏻 서비스 소개
NINE Cloud는 매일 하나의 일기를 작성하며 자신의 감정을 되돌아보고 AI 솔루션을 받는 감정일기 서비스입니다.
## 
## 🌞프로젝트 소개
[FE] : CRUD, AI접목, Socket을 이용한 채팅기능, 무한스크롤, canvas사용, OAuth구현
[BE] : CRUD, OAuth로그인, Socket을 활용한 채팅기능, S3를 활용한 이미지 업로드, 자동화배포 CI/CD에 Docker, Nginx를 추가해 무중단배포 파이프라인 구축

[사용자] : 바쁘게 살아가는 현대인들을 위해, 자신의 하루 감정을 날씨와 연관 지어 돌아볼 수 있는 다이어리
##

## 📂 Project GitHub
[FE] : https://github.com/final-project-hh99/front.git
[BE] : https://github.com/Lee-chan0/final_project_back
## 

## ⛅️ 팀원 소개 (👨‍👩‍👧‍👦구르미들)

- **Back End**
  - 유재현(부리더)([https://github.com/yjhorion](https://github.com/yjhorion))
    1. Main달력
    2. feed생성
    3. multer-S3 이미지 업로드
    4. socket.io 채팅기능
  - 이찬영([https://github.com/Lee-chan0](https://github.com/Lee-chan0))
    1. SignIn, SignUp
    2. OAuth
    3. CI/CD, 인프라
    4. DevOps
- **Front End**
  - 주철민(리더)([https://github.com/cheolminJOO](https://github.com/cheolminJOO))
  - 송지우([https://github.com/nsong113](https://github.com/nsong113))
  - 한덕용([https://github.com/HyperQuanx](https://github.com/HyperQuanx))
- **Designer**
  - 이승연([20211009@sungshin.ac.kr](20211009@sungshin.ac.kr))

## ❄️ Project Architecture

![Untitled Diagram.drawio (3).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/83c75a39-3aba-4ba4-a792-7aefe4b07895/5d9a3881-fc33-488d-9a19-a0b65f1c48d2/Untitled_Diagram.drawio_(3).png)

## Stacks

<div align="center">
  <h1>🛠 Tech Stack</h1>
  <p>
    <img src="https://img.shields.io/badge/javascript-F0DB4F?style=for-the-badge&logo=javascript&logoColor=black">
    <img src="https://img.shields.io/badge/node.js-68A063?style=for-the-badge&logo=Node.js&logoColor=white">
    <img src="https://img.shields.io/badge/express-FF6C37?style=for-the-badge&logo=express&logoColor=white">
  </p>
</div>

<div align="center">
  <h1>🗄️ DB / ORM</h1>
  <p>
    <img src="https://img.shields.io/badge/mysql-00758F?style=for-the-badge&logo=mysql&logoColor=white">
    <img src="https://img.shields.io/badge/mongoDB-12924F?style=for-the-badge&logo=MongoDB&logoColor=white">
    <img src="https://img.shields.io/badge/Redis-C92B2B?style=for-the-badge&logo=redis&logoColor=white">
    <img src="https://img.shields.io/badge/Prisma-2A7AE4?style=for-the-badge&logo=Prisma&logoColor=white">
  </p>
</div>

<div align="center">
  <h1>🖥️ CI/CD & DevOps</h1>
  <p>
    <img src="https://img.shields.io/badge/github-6E5494?style=for-the-badge&logo=github&logoColor=white">
    <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
    <img src="https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white">
    <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
    <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
    <img src="https://img.shields.io/badge/AWS%20CodeDeploy-FF7F00?style=for-the-badge&logo=aws&logoColor=white">
    <img src="https://img.shields.io/badge/Docker%20Compose-DA70D6?style=for-the-badge&logo=docker&logoColor=white">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
    <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
  </p>
</div>

<div align="center">
  <h1>📜 Library & Monitoring & Communication</h1>
  <p>
    <img src="https://img.shields.io/badge/socket.io-FF4081?style=for-the-badge&logo=socket.io&logoColor=white">
    <img src="https://img.shields.io/badge/JWT-00B2A9?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
    <img src="https://img.shields.io/badge/Swagger-E3E569?style=for-the-badge&logo=swagger&logoColor=white">
    <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
    <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white">
    <img src="https://img.shields.io/badge/Notion-8B8B8B?style=for-the-badge&logo=notion&logoColor=white">
    <img src="https://img.shields.io/badge/Slack-E01E5A?style=for-the-badge&logo=slack&logoColor=white">
  </p>
  <br>
</div>

## 🌧 Library

|       library       |                         description                         |
| :-----------------: | :---------------------------------------------------------: |
|       dotenv        |            보안적으로 문제가 있는 데이터 숨기기             |
|        cors         |            CORS보안 정책을 해결하기 위하여 사용.            |
|       bcrypt        |         해시함수를 사용하여 암호화 하기 위해 사용.          |
|         joi         |                    Validate를 위해 사용.                    |
|   @slack/webhook    |                slack 채팅을 하기 위해 사용.                 |
|     compression     |                페이지를 압축하기 위해 사용.                 |
|       express       |       빠르고 개방적인 개발을 위해 웹 프레임워크 사용.       |
|    jsonwebtoken     |                    JWT Token 위해 사용.                     |
|  morgan, wingston   |                에러 로그 관리하기 위해 사용.                |
|       mysql2        |           Node.js에서 MySQL을 사용하기 위해 사용.           |
|      artillery      |             서버 부하테스트 하기 위해 사용한다.             |
|       multer        |                         파일 업로드                         |
|      multer-s3      |                      S3에 파일 업로드                       |
| multer-s3-transform |           upload시 자동으로 파일을 변형시켜준다.            |
|    swagger-jsdoc    | 주석에 Swagger 태그를 추가하여 API를 문서화 하기 위해 사용. |
| swagger-ui-express  |            API 문서를 UI 렌더링 하기 위해 사용           |
|       helmet        |            서버 어플리케이션의 보안을 위해 사용             |

## 🔎 API

[Notion API Address](https://www.notion.so/API-22f9456b7c254576b2a9cbc101c603d1)

![캡처2](https://github.com/Lee-chan0/nomyproject/assets/147553654/b42a681c-1e56-4a08-94de-b601727e39a3)
![캡처3](https://github.com/Lee-chan0/nomyproject/assets/147553654/980c3de8-3e8f-46b9-bd2c-2e5a0aedf415)
![캡처4](https://github.com/Lee-chan0/nomyproject/assets/147553654/3ff9b052-0a8b-401c-b714-823ab3920227)

## 📋 ERD

![ERD](./readme_images/erd2.png)

## ✅ 향후 프로젝트의 목표
