# ☁ Cloud NINE

## ✍🏻 서비스 소개
Cloud NINE은 ,그날의 감정을 기록하고, 다른사람들과 그 감정을 그림과 일기로 공유하는 서비스입니다.
## 

## ⛅️ 팀원 소개

- **Back End**
  - 유재현(부리더)([https://github.com/yjhorion](https://github.com/yjhorion))
  - 이찬영([https://github.com/Lee-chan0](https://github.com/Lee-chan0))
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

[Notion API Address](https://humble-impulse-a58.notion.site/API-ea80617bb56e4488807877a15ad2a3c2)

![backend-at]()

![API-1](readme_images/https://github.com/Lee-chan0/nomyproject/assets/147553654/7bfd5d4c-59a7-4f3a-a368-411c96a2a55e)
![API-2](readme_images/api-2.png)
![API-3](readme_images/api-3.png)

## 📋 ERD

![ERD](./readme_images/erd2.png)

## ✅ 향후 프로젝트의 목표
