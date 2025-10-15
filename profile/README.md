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
  <summary>송용훈(FS) : "완성은 끝이 아니라, 더 깊이 들어가는 시작이었다"</summary>
  <table>
    <tr>
      <td align="center" width="160">
        <img src="https://raw.githubusercontent.com/yonghun16/yonghun16/main/images/profile.jpeg" width="160" height="160" />
      </td>
      <td>
        <p>
          이번 프로젝트에서 저는 서비스의 중앙이 되는 API 아키텍처를 설계하고,<br />
          인증, 주문, 결제, 로그 전달 등 여러 시스템이 유기적으로 연결되도록 만들었습니다.<br />
          모든 기능이 안정적으로 돌아가는 순간이 찾아왔지만, 그때 오히려 ‘이제 진짜 시작이구나’ 하는 생각이 들었습니다.<br /><br />
          API 하나를 완성할 때마다 더 나은 구조와 더 효율적인 데이터 흐름을 고민하게 되었고,<br />
          그 과정에서 개발은 단순히 코드를 완성하는 일이 아니라,<br />
          끊임없이 더 나은 방법을 탐구하는 여정이라는 걸 깨달았습니다.
        </p>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary>노인영(FS) : "I wanted every flow to connect naturally."</summary>
  <table>
    <tr>
      <td align="center" width="160">
        <img src="https://raw.githubusercontent.com/yonghun16/yonghun16/main/images/profile.jpeg" width="160" height="160" />
      </td>
      <td>
        <p>
          While developing the Admin Dashboard, I focused not just on building simple CRUD interfaces, but on crafting a “Golden Path” where the user’s flow remains uninterrupted.<br /><br />
          I connected product and promotion management logic seamlessly across both frontend and backend, implementing authentication and data visualization to create a structure that administrators can intuitively understand and operate.<br />
          Throughout the process, I realized that what truly matters is not just how well something works, but how well it is experienced.<br /><br />
          This project became a turning point for me — a reminder to always seek the right balance between functionality and user experience.
        </p>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary>이정관(FS) : "기능은 완성이 아니라 경험으로 완성된다."</summary>
  <table>
    <tr>
      <td align="center" width="160">
        <img src="https://raw.githubusercontent.com/yonghun16/yonghun16/main/images/profile.jpeg" width="160" height="160" />
      </td>
      <td>
        <p>
          User Web App을 개발하면서 가장 많이 고민했던 건, 단순히 로그인이나 주문이 ‘된다’가 아니라 사용자가 자연스럽게 느끼는 흐름이었습니다.<br />
          하나의 화면이 끝나면 다음 행동이 이어지도록, 그리고 데이터가 언제나 정확하게 반응하도록 세심하게 다듬었습니다.<br />
          특히 실시간 로그 전송과 배치 처리를 안정화하면서, 사용자의 행동이 곧 서비스의 신뢰로 이어진다는 걸 실감했습니다.<br /><br />
          결국 이번 프로젝트는 “작동하는 기능”보다 “느껴지는 경험”이 얼마나 중요한지를 다시 깨닫게 해준 시간이었습니다.
        </p>
      </td>
    </tr>
  </table>
</details>

<details>
  <summary>이세준(BE) : "보이지 않는 곳에서 흐름을 만든다는 것."</summary>
  <table>
    <tr>
      <td align="center" width="160">
        <img src="https://raw.githubusercontent.com/yonghun16/yonghun16/main/images/profile.jpeg" width="160" height="160" />
      </td>
      <td>
        <p>
          이번 프로젝트에서 저는 사용자 행동 로그를 수집하고, 가공하고, 추천으로 이어지는 데이터의 흐름을 설계했습니다.<br />
          직접 눈에 보이지 않는 백그라운드 작업이지만, 그 흐름이 안정적으로 이어질 때 서비스 전체가 살아 움직인다는 걸 느꼈습니다.<br />
          실시간 처리와 배치 작업을 조율하며, 시스템의 ‘속도’보다 더 중요한 건 ‘균형’과 ‘신뢰성’이라는 사실을 배웠습니다.<br /><br />
          이 경험은 제가 데이터를 다룰 때 단순한 기술 구현을 넘어, 흐름을 설계하는 엔지니어로 성장하는 계기가 되었습니다.
        </p>
      </td>
    </tr>
  </table>
</details>


## ⚙️ 기술 스택
- **언어** : <!-- TypeScript --><a href="https://www.typescriptlang.org"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white" /></a> <!-- JavaScript --><a href="https://www.ecma-international.org/"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" /></a>
- **프레임 워크** : <!-- Next.js --><a href="https://nextjs.org"><img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=Next.js&logoColor=white" /></a> <!-- Express.js --><a href="https://expressjs.com/"><img src="https://img.shields.io/badge/Express-000000?style=flat&logo=Express&logoColor=white" /></a>
- **캐시 서버** : <!-- Redis --><a href="https://redis.io"><img src="https://img.shields.io/badge/Redis-FF4438?style=flat&logo=Redis&logoColor=white" /></a>
- **데이터 베이스** : <!-- MongoDB --><a href="https://www.mongodb.com/"><img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=MongoDB&logoColor=white" /></a> <!-- ClickHouse --><a href="https://clickhouse.com/"><img src="https://img.shields.io/badge/ClickHouse-FFCC01?style=flat&logo=ClickHouse&logoColor=white" /></a> <!-- milvus --><a href="https://milvus.io/ko"><img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat&logo=Milvus&logoColor=white" /></a>
- **번들, 배포** : <!-- Turborepo --><a href="https://turborepo.com/"><img src="https://img.shields.io/badge/Turborepo-FF1E56?style=flat&logo=Turborepo&logoColor=white" /></a> <!-- OCI --><a href="https://www.oracle.com/cloud/"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=Oracle&logoColor=white" /></a> 
- **기타** : <!-- mongoose --><a href="https://mongoosejs.com/"><img src="https://img.shields.io/badge/Mongoose-880000?style=flat&logo=Mongoose&logoColor=white" /></a> <!-- Zustand --><a href="https://zustand-demo.pmnd.rs/"><img src="https://img.shields.io/badge/Zustand-FF9551?style=flat&logo=Zustand&logoColor=white" /></a> <!-- React Router --><a href="https://reactrouter.com"><img src="https://img.shields.io/badge/React_Router-CA4245?style=flat&logo=React%20router&logoColor=white" /></a> <!-- React Query --><a href="https://tanstack.com/query/latest"><img src="https://img.shields.io/badge/React_Query-FF4154?style=flat&logo=React%20query&logoColor=white" /></a> <!-- React Hook Form --><a href="https://react-hook-form.com"><img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat&logo=React%20hook%20form&logoColor=white" /></a> <!-- Tailwind CSS --><a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white" /></a>


## 🧩 기능 소개
### 🔑 로그인 및 회원가입
![로그인_회원가입](https://github.com/Bugs-Star/.github/blob/main/profile/profileimgs/login.gif?raw=true)
### 🛍️ 메인 상품 보기 & 장바구니 & 결제
![메인 상품 보기 결제](https://github.com/Bugs-Star/.github/blob/main/profile/profileimgs/menu.gif?raw=true)
### 👀 사용자 로그 수집
![로그 수집](https://github.com/Bugs-Star/.github/blob/main/profile/profileimgs/log.gif?raw=true)
### 🛠️ 상품, 프로모션, 이벤트 생성 수정 삭제
### 🔀 프로모션, 이벤트 순서 변경
### 📊 집계 자료 확인(매출, 베스트셀러, 사용자 활동, 골든패스 등)

## 🔗 바로 가기
- [Notion](https://www.notion.so/2454a00d5d0580b3a9fbedf3a4cf9085)
- Architecture Diagram
- [UI/UX](https://app.visily.ai/projects/d4b06ddb-7f9c-4c37-aac6-77146746ca1e/boards/2092920)
- [ERD](https://lucid.app/lucidchart/ecc38e76-f593-4c6f-880b-48860d441eaf/edit?invitationId=inv_89628339-73bf-4361-9b41-8c3ae5e751e6&page=8axG5UtdnnNm#)
- Use Case
