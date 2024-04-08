
<section align="end" style="color: #fff;">
  <p>${\small\texttt{\color{#a9a9a9} last 23.04.02}}$</p>
</section>

<section align="center">

<a href="https://www.pintogether.co.kr" >
<img src="https://github.com/PinTogether/.github/assets/89989211/205a7826-36d3-421f-95a2-d09bb9864d9b" alt="pintogether-logo-horizontal" width="300"/>
</a>

</section>

<br/>
<br/>
<br/>

<section>
   <h2> 목차 </h2>
  
  1. [소개](#-소개-Introduction) 
  2. [프로젝트 진행 기간](#-프로젝트-진행-기간)
  3. [제공하는 기능](#-제공하는-기능)
  4. [팀원 소개](#-팀원-소개)
  5. [서비스 화면](#-서비스-화면)
  6. [사용 기술](#-사용-기술)
  7. [아키텍쳐](#-아키텍쳐-Architecture)
  8. [API](#-API)
  9. [ERD](#-ERD)
  
</section>
<br/>

<section>

  ## 📌 소개 Introduction

  >  [pintogether.co.kr](https://www.pintogether.co.kr) <br/>
  >  좋아하는 장소에 핀을 찍고, 컬렉션을 만들어 친구들과 공유해보세요!  <br/>
  
  <br/>
  Pintogether는 지도를 기반으로 한 장소 공유 웹 서비스 프로젝트입니다.  <br/>
  <br/>

  타인이 알고있는 맛집과 장소들을 한눈에 확인하고 손쉽게 탐색하기 어렵다는 일상의 불편함에서 출발했습니다. <br/>
  이를 해소하기 위해 웹 기반의 장소 목록 서비스를 구상하게 되었습니다. <br/>
  사용자들이 맛집리스트를 발견하고 공유하는 즐거움을 쉽고 편리하게 누릴수 있는 서비스를 추구합니다. <br/>
  
  <br/>

  <h2>📌 프로젝트 진행 기간</h2>

  설계 및 주요 기능 구현 : 24.01.15 ~ 03.31

  실제 서비스 배포를 위한 리펙토링 : 24.04.01 ~ 개발중

  <br/>


  <h2>📌 제공하는 기능</h2>

  * 소셜로그인
  * 장소 검색
    * 현재 LOCALDATA(지방행정 인허가 데이터 개방)에서 가져온 음식점 데이터 약 25만건을 기반으로, 장소 검색기능을 제공하고 있습니다.
    * 장소 검색 기록 조회
  * 지도
  * 프로필 조회, 수정
    * 유저 팔로우
  * 컬렉션(장소목록)
    * 컬렉션 조회, 수정
    * 컬렉션 좋아요, 스크랩
  * 핀(장소저장)
    * 핀 조회, 수정
    * 핀 좋아요
  * 장소 찜
    * 찜한 장소 컬렉션에 핀으로 저장
  * 알림
  * 신고
  * 인기 컬렉션 추천
  * 컬렉션 공유


</section>

<br/>


<section >
  <h2>📌 팀원 소개</h2>
  <table align=center>
    <thead>
      <tr>
          <td align=center width="500">😶</td>
          <td align=center width="500">😶</td>
          <td align=center width="500">😶</td>
          <td align=center width="500">🥰</td>
      </tr>
    </thead>
      <tr>
          <td align=center><a href="https://github.com/jwo1024">이지우(팀장)</a></td> 
          <td align=center><a href="https://github.com/UMGGG">전재영</a></td>
          <td align=center><a href="https://github.com/tehyoyee">김태형</a></td>
          <td align=center><a href="https://github.com/spew11">이은지</a></td>
      </tr>
      <tr>
          <td align=center>프론트엔드, 기획, 디자인</td>
          <td align=center>프론트엔드</td>
          <td align=center>백엔드, 인프라(클라우드), CI/CD</td>
          <td align=center>백엔드, 인프라(클라우드)</td>
      </tr>
      <tr>
          <td align=center>
            - 로그인 페이지<br/>
            - 프로필, 컬렉션, 핀 조회 및 수정 페이지<br/>
            - 유저 팔로우, 컬렉션 좋아요 스크랩, 핀 좋아요, 장소 찜하기 기능<br/>
          </td>
          <td align=center>
            - Naver Map api <br/>
            - 
          </td>
          <td align=center>
            - ERD/API (1/3)<br/>
            - 로그인 (JWT, OAuth)<br/>
            - 검색<br/>
            - 지도 데이터 수집<br/>
            - Elastic Stack (ING)<br/>
            - CI/CD 깃허브액션<br/>
            - AWS 관리<br/>
          </td>
          <td align=center>
            - 전반적인 DB설계 및 엔티티 매핑<br/>
            - 전반적인 API설계 <br/>
            - 멤버, 컬렉션, 알림 API 구현 <br/>
            - 웹 소켓 기반 알림 구현 <br/>
          </td>
      </tr>
  </table>
</section>
<br/>

<section>
  <h2>📌 서비스 화면</h2>

  * 서비스 페이지별로
  * 지도
  * 홈
    * 추천 컬렉션
  * 프로필 
    * 조회
    * 수정
    * 팔로우
    * 설정
  * 컬렉션
   * 조회
   * 생성/수정
   * 찜
   * 댓글
  * 장소 조회
  * 검색
    * 검색 기록
    * 장소 / 컬렉션 검색
  * 신고
  * 알림

  * 공유하기 기능 - Open Graph 적용
  
<section>
  <h2>📌 사용 기술</h2>

  ### Backend
  * Java 17
  * Spring Boot 3.2.2
  * SpringSecurity(OAuth2, JWT)
  * Spring Data JPA
  * Spring Cloud-aws 2.2.6
  * Spring Websocket

  ### Frontend
  * HTML/CSS
  * Typescript 5.0
  * Next.js 14.1.0
  * React 18
  * Redux 5.0.1
  * SCSS 0.2.4
  * ESLint

  ### DB
  * MariaDB 10.11.6
  * Elastic Stack(Beats, Logstash, ElasticSearch, Kibana) 개발중

  ### Open API
  * [Naver Cloud Maps(Web Dynamic Map)](https://www.ncloud.com/product/applicationService/maps)
  * [SGIS Geocode](https://sgis.kostat.go.kr/view/index)
  * [GeoLocation](https://w3c.github.io/geolocation-api/#geolocation_interface)

  ### 데이터
  * [LOCALDATA(지방행정 인허가 데이터 개방)](https://www.localdata.go.kr/main.do)

  ### AWS
  * Elastic Beanstalk(EC2, Application LoadBalencer, CloudWatch)
  * Amplify
  * S3(presgined-url)
  * Route53
  * RDS

  ### CI/CD
  * Github Action
  * Git Submodule

  ### 도구
  * VScode
  * IntelliJ IDEA
  * MySQLWorkbench
  * Postman
  * Vercel (프론트 페이지 테스트 용도)

  ### 협업
  * Notion
  * Slack

  ### 디자인
  * Figma

</section>


<section>
  <h2>📌 아키텍쳐 Architecture</h2>
  <img src="https://github.com/PinTogether/.github/assets/89989211/dc58d944-f6ea-498b-908d-5f9dff6834ce" alt="pintogether-architecture" width="800"/>

  <h2>📌 Api</h2>
  * API Notion Link
  <img src="https://github.com/PinTogether/.github/assets/95565246/0a07c184-5323-44a2-95c1-11b0f81548c6" alt="pintogether-api" />

  <h2>📌 ERD</h2>
  <img src="https://github.com/PinTogether/.github/assets/95565246/f84a0533-1f3b-4d17-a2ec-6c2c8af6631e" alt="pintogether-erd" />

</section>



