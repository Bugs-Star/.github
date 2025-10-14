# ☕️ 카페 앱 행동 분석 시스템(벅스스타)

<div align="center">
<img src="https://github.com/Bucks-Star/.github/blob/main/profile/profileimgs/image.png" alt="메인" width="800" />
</div>

## 📝 프로젝트 개요
![project_period](https://img.shields.io/badge/Project%20Period-2025--08--04%20~%202025--09--20-024d28)<br>

본 프로젝트는 카페 이용 고객을 위한 모바일 주문 시스템으로, 

음료 및 메뉴 주문 기능은 물론, **사용자 행동 데이터를 수집 및 분석**하여 **운영자에게 실시간 통계 및 인사이트를 제공하는 대시보드 기능**을 포함합니다. 

일반적인 주문 앱 기능을 바탕으로, 고객 경험 향상과 운영 효율성을 함께 도모하는 것이 핵심입니다.

## 📦 배포

### 📱 User Web App
> https://bugs-star-web.vercel.app/
  - ID : web@web.web
  - PW : webweb

### 👩‍💻 Admin Dashboard App
> https://bugs-star-admin.vercel.app/
  - ID : admin@admin.admin
  - PW : admin

## 💁🏻 팀원
<table>
  <thead>
    <tr>
      <th style="white-space: nowrap;">프로필&nbsp;&nbsp;&nbsp;&nbsp;</th>
      <th>이름(포지션) - 작업 내역</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td rowspan="2" style="vertical-align: top; padding: 10px;">
        <img src="https://github.com/fantasy-shop/.github/blob/main/profile/project_info/pic1.png?raw=true" alt="송용훈" style="min-width: 50px; width:60px; height: 60px;" />
      </td>
      <td><a href="https://github.com/yonghun16">송용훈</a> (FS - API, UI/UX Design)</td>
    </tr>
     <tr>
      <td colspan="2">Auth API, 백엔드 아키텍처, 주문/결제/행동 데이터 처리, 로그 전달 API, Dashboard 통계 API, UI/UX 구조 설계</td>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td rowspan="2" style="vertical-align: top; min-width: 50px;">
        <img src="https://github.com/fantasy-shop/.github/blob/main/profile/project_info/pic4.png?raw=true" alt="노인영" style="min-width: 50px; width:60px; height: 60px;" />
      </td>
      <td><a href="https://github.com/ines2131/">노인영</a> (FS - Screen, Golden Path & ReOrder Logic)</td>
    </tr>
     <tr>
       <td colspan="2">Admin Dashboard Auth 로직, 상품·등록·수정·삭제, Item/Promotion 순서 로직(FE & BE), Golden Path 구현, 데이터 후처리 및 시각화
</td>
     </tr>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td rowspan="2" style="vertical-align: top; min-width: 50px;">
        <img src="https://github.com/fantasy-shop/.github/blob/main/profile/project_info/pic3.png?raw=true" alt="이정관" style="min-width: 50px; width:60px; height: 60px;" />
      </td>
      <td><a href="https://github.com/LEEJUNGKWAN1">이정관</a> (FS - Screen, Refresh token-based security)</td>
    </tr>
      <tr>
        <td colspan="2">User Web App Auth 로직(리플레시 토큰 기반 보안 포함), 상품 조회·주문·결제, 사용자 행동 데이터 수집(배치·실시간) 및 전처리</td>
      </tr>
    </tr>
  </tbody>
  <tbody>
    <tr>
      <td rowspan="2" style="vertical-align: top; min-width: 50px;">
        <img src="https://github.com/fantasy-shop/.github/blob/main/profile/project_info/pic5.png?raw=true" alt="이세준" style="min-width: 50px; width:60px; height: 60px;" />
      </td>
      <td><a href="https://github.com/hello22433/">이세준</a> (BE - Data processing oversight )</td>
    </tr>
      <tr>
        <td colspan="2">데이터 흐름 설계, Log/Recommendation Worker 구현, 사용자 행동 로그 전처리·후처리(ClickHouse, Milvus), 맞춤형 추천</td>
      </tr>
    </tr>
  </tbody>
</table>

<!--

- **송용훈(FS)** : API Server
  - 웹 및 Admin용 인증(Auth) API 설계 및 구현
  - 백엔드 아키텍처 전반을 설계하고, 데이터 흐름과 API 안정성을 최적화
  - 주문, 결제, 사용자 행동 데이터 처리 등 핵심 비즈니스 로직과 API 개발
  - 수집된 사용자 행동 로그 데이터를 Worker로 전달하는 Log Data Delivery API 구현
  - Admin Dashboard에서 실시간 통계 및 인사이트 제공을 위한 Dashboard Data API 설계 및 구현
- **노인영(FS)** : Admin Dashboard App
  - Admin Dashboard의 주요 화면(Items, Promotions, Events) 설계 및 프론트엔드 구현
  - CRUD 기능 전반을 프론트에서 구현하고, 사용자 인터랙션과 상태 관리를 최적화
  - Items의 순서 변경 및 Promotion 우선순위 로직을 프론트와 백엔드에서 연동하여 구현
  - 운영자가 데이터를 직관적으로 이해할 수 있도록 통계 및 데이터 시각화 구현
- **이정관(FS)** : User Web App
  - 사용자 로그인, 회원가입, 프로파일 관리 기능 설계 및 구현
  - 전체 User Web App의 UI/UX와 기능 흐름 설계, 사용자 경험 최적화
  - 상품 목록 조회, 상세 정보 확인, 주문 처리 등 주요 사용자 기능 개발
  - 사용자의 행동 데이터를 배치 및 실시간 전송을 통해 수집 Data의 소실을 최소화하여 전송하는 기능 구현
- **이세준(FS)** : Log Worker, Recommendation Worker
  - 사용자 행동 로그를 가공, 처리, 저장하여 ClickHouse, Milvus 등 전용 DB에 적재
  - 실시간 또는 배치 방식으로 로그 데이터를 처리하는 Log Worker 구현
  - 추천 시스템(Recommendation Worker) 구현, 사용자 행동 데이터 기반으로 맞춤형 추천 제공
  - 백그라운드 작업(Worker) 설계 및 최적화, 서버 부하를 고려한 안정적 데이터 처리
  - 데이터 흐름과 Worker 간 연계 로직을 설계하여 전체 시스템 효율성 향상
-->

## ✨ 프로젝트 후기
<details>
  <summary>송용훈(FS) : "완성은 끝이 아니라 시작이라는 걸 느꼈습니다" </summary>
  <table>
  <tr>
    <td align="center" style="padding-right: 20px;">
      <img src="https://github.com/yonghun16/yonghun16/blob/main/images/profile.jpeg?raw=true" width="150" alt="대표 이미지" />
    </td>
    <td>
      <p>
        프로젝트를 끝내고 나니, 코드와 기능이 완성된 기쁨보다 아직 배우고 성장할 게 많다는 생각이 더 크게 다가왔습니다.<br />
        하나를 완성할 때마다 새로운 궁금증과 도전이 생기고, 그 과정에서 배움은 끝나지 않는다는 걸 깨달았습니다.<br /><br />
        이번 경험을 통해, 완성은 단지 다음 시작을 위한 발판이라는 걸 몸소 느낄 수 있었습니다.
      </p>
    </td>
  </tr>
</table>
</details>




## ⚙️ 기술 스택
- **언어** : <!-- TypeScript --><a href="https://www.typescriptlang.org"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white" /></a> <!-- JavaScript --><a href="https://www.ecma-international.org/"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" /></a>
- **프레임 워크** : <!-- Next.js --><a href="https://nextjs.org"><img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=Next.js&logoColor=white" /></a> <!-- Express.js --><a href="https://expressjs.com/"><img src="https://img.shields.io/badge/Express-000000?style=flat&logo=Express&logoColor=white" /></a>
- **캐시 서버** : <!-- Redis --><a href="https://redis.io"><img src="https://img.shields.io/badge/Redis-FF4438?style=flat&logo=Redis&logoColor=white" /></a>
- **데이터 베이스** : <!-- MongoDB --><a href="https://www.mongodb.com/"><img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=MongoDB&logoColor=white" /></a> <!-- mongoose --><a href="https://mongoosejs.com/"><img src="https://img.shields.io/badge/Mongoose-880000?style=flat&logo=Mongoose&logoColor=white" /></a> <!-- ClickHouse --><a href="https://clickhouse.com/"><img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat&logo=ClickHouse&logoColor=white" /></a> <!-- milvus --><a href="https://milvus.io/ko"><img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat&logo=Milvus&logoColor=white" /></a>
- **번들, 배포** : <!-- Turborepo --><a href="https://turborepo.com/"><img src="https://img.shields.io/badge/Turborepo-FF1E56?style=flat&logo=Turborepo&logoColor=white" /></a> <!-- OCI --><a href="https://www.oracle.com/cloud/"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=Oracle&logoColor=white" /></a> 
- **기타** : <!-- Zustand --><a href="https://zustand-demo.pmnd.rs/"><img src="https://img.shields.io/badge/Zustand-FF9551?style=flat&logo=Zustand&logoColor=white" /></a> <!-- React Router --><a href="https://reactrouter.com"><img src="https://img.shields.io/badge/React_Router-CA4245?style=flat&logo=React%20router&logoColor=white" /></a> <!-- React Query --><a href="https://tanstack.com/query/latest"><img src="https://img.shields.io/badge/React_Query-FF4154?style=flat&logo=React%20query&logoColor=white" /></a> <!-- React Hook Form --><a href="https://react-hook-form.com"><img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat&logo=React%20hook%20form&logoColor=white" /></a> <!-- Tailwind CSS --><a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white" /></a>


## 🧩 기능 소개

## 🔗 바로 가기
- [Notion](https://www.notion.so/2454a00d5d0580b3a9fbedf3a4cf9085)
