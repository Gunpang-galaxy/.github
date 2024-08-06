<div align="center">
    <img src="../image/Banner_top.png" alt="Logo">
</div>

<div align="center">
    <h1>📑 목차 📑</h1>
</div> 

<!-- [1. 서비스 소개]() <br/>
[2. 기술 스택]() <br/>
[3. 설계문서]() <br/>
[3.1. 서비스 구조도]() <br/>
[3.2. 화면 설계서]() <br/>
[3.4. ER Diagram]() <br/>
[3.2. 시스템 아키텍쳐]() <br/>
[3.5. 빅데이터 파이프라인]()<br/>

[4.프로젝트 요약]() <br/>
[4.1. 기간/인원/역할]()
[4.2. 소스코드]() -->

<div>
    <ul>
        <li><a href="#-1-서비스-소개-">1. 서비스 소개(Service Introduction)</a></li>
        <li><a href="#--2-기술스택--">2. 기술스택 (Technology Stack)</a></li>
        <li>
            <a href="#--3-설계-문서-">3. 설계 문서 (Design Documents)</a>
            <ul>
                <li><a href="#-31-서비스-구조도">3.1. 서비스 구조도 (Service Structure)</a></li>
                <li><a href="#-32-화면-설계서-">3.2. 화면 설계서 (Screen Design)</a></li>
                <li><a href="#-33-er-diagram-">3.3. ER Diagram</a></li>
                <li><a href="#34-api-명세서">3.4. API 명세서 (API Specification)</a></li>
                <li><a href="#-35-시스템-아키텍쳐-">3.5. 시스템 아키텍쳐 (System Architecture)</a></li>
                <li><a href="#-36-빅데이터-파이프라인">3.6. 빅데이터 파이프라인 (Big Data Pipeline)</a></li>
            </ul>
        </li>
        <li>
            <a href="#--4-프로젝트-요약--">4. 프로젝트 요약 (Project Summary)</a>
            <ul>
                <li><a href="#-41-기간인원역할-">4.1. 기간/인원/역할</a></li>
                <li>
                    <a href="#-42-소스코드-">4.2. 소스코드 (Source Code)</a>
                    <ul>
                        <li><a href="https://github.com/Gunpang-galaxy/gunpang-frontend">프론트앤드(Frontend)</a></li>
                        <li><a href="https://github.com/Gunpang-galaxy/gunpang-backend-public">백엔드(Backend)</a></li>
                        <li><a href="https://github.com/Gunpang-galaxy/gunpang-bigdata">빅데이터(Big Data)</a></li>
                    </ul>
                </li>
            </ul>
        </li>
    </ul>
</div>

<br/>
<div align="center">
    <h1>⌚ 1. 서비스 소개 ⌚</h1>
    <a href="https://youtu.be/hlwR0wIwFvc">
    <img src="./image/gunpang_logo.png" width="100px"/>
    </a>
    <p>
    ↑ 사진을 클릭하면 UCC를 볼 수 있어요↑  
    </p>
</div> 


건팡은 스마트 워치를 활용한 `사용자 라이프 개선 애플리케이션`입니다.

아바타 성장으로 `동기를 부여`하고 워치의 센서를 이용해 `건강 데이터를 측정`하여 `생활 습관을 개선`할 수 있습니다.

<br/>

<h2> 주요 기능</h2>


### 1) 아바타 성장 및 목표 설정

랜덤하게 선택된 아바타에 이름을 붙이고 아바타를 키우며 지킬 생활 습관 목표를 입력할 수 있습니다.
<div align="center">
    <img src="./image/main_screen.jpg" width="100px" alt="건팡 메인 화면"/>
</div>

### 2) 식사 시간 알림

꾸준한 식사 기록을 위해 식사 시간에 앱 푸시 알림을 전송합니다.
<div align="center">
    <img src="./image/push_alert.png" width="300px" alt="건팡 알림"/>
</div>

### 3) 운동 상태 측정

스마트 워치를 이용하여 운동 진행 시간을 기록하고 심박수를 측정하여 운동 강도를 파악합니다.

<div align="center">
    <img src="./image/exercise.jpg" width="400px" alt="워치 운동 측정"/>
</div>

<br/>

<div align="center">
   <h1> 🛠 2. 기술스택 🛠 </h1>
</div>

#### Android

<img src="https://img.shields.io/badge/KOTLIN-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/JETPACK COMPOSE-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white"/>


#### Backend

<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/spring batch-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/JPA Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"> <img src="https://img.shields.io/badge/Query DSL-3E87D0?style=for-the-badge">

<img src="https://img.shields.io/badge/FIREBASE-FFCA28?style=for-the-badge&logo=firebase&logoColor=white"> <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white"> <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">


#### Database

<img src="https://img.shields.io/badge/MYSQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/REDIS-DC382D?style=for-the-badge&logo=redis&logoColor=white">


#### Big Data

<img src="https://img.shields.io/badge/APACHE SPARK-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"> <img src="https://img.shields.io/badge/APACHE HADOOP-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=white"> <img src="https://img.shields.io/badge/apache kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white">

#### Infra

<img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"> <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">


#### IDE

<img src="https://img.shields.io/badge/intellijidea-000000?style=for-the-badge&logo=intellijidea&logoColor=white"> <img src="https://img.shields.io/badge/androidstudio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white">

#### Collaboration

<img src="https://img.shields.io/badge/mattermost-0058CC?style=for-the-badge&logo=mattermost&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000.svg?&style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white">





<div align="center">
    <h1> 💻 3. 설계 문서 💻</h2>
</div>

<h2> 3.1. 서비스 구조도</h2>

![서비스 구조도](./image/service_architecture.png)


<h2> 3.2. 화면 설계서 </h2>
<div align="center">
    <img src="./image/" width="100%" alt="화면 설계 "/>
</div>

<br/>

<h2> 3.3. ER Diagram </h2>
<div align="center">
    <img src="./image/ERD.jpg" width="100%" alt="ER Diagram"/>
</div>

<br/>

<h2>3.4. API 명세서</h2>
<div align="center">
    <img src="./image/api_description.png" width="60%" alt="ER Diagram"/>
</div>

<br/>

<h2> 3.5. 시스템 아키텍쳐 </h2>
<div align="center">
    <img src="./image/system_architecture.png" width="100%" alt="시스템 아키텍쳐"/>
</div>

- **Firebase Cloud Messaging**을 통해 앱 푸시 알림 기능을 구현
- **redis**를 이용하여 JWT 관리
- **hadoop**을 이용하여 1초에 1개씩 발생하는 심박수 데이터 처리
- **Jenkins**를 이용하여 dev 브랜치에 코드 merge 시 서버 자동 빌드


<h2> 3.6. 빅데이터 파이프라인</h2>
<div align="center">
    <img src="./image/bigdata_pipeline.jpg" width="100%" alt="빅데이터 파이프라인"/>
</div>


- 1초 당 발생하는 심박수 데이터를 **socket 통신**을 이용하여 **kafka**의 특정 Topic에 발행
- Spark를 이용하여 kafka에서 읽어 데이터를 HDFS에 적재



<div align="center">
    <h1> 🍰 4. 프로젝트 요약 🍰 </h2>
</div>
<h2> 4.1. 기간/인원/역할 </h2>

- 2023.10.09 ~ 2023.11.17 (6주)
- 6명

| 박은정(팀장) | 권기윤 | 박수빈 | 박예한 | 양우철 | 이정민 |
| --- | --- | --- | --- | --- | --- |
| ![팀원](./image/team_pej.jpg) | ![팀원](./image/team_kky.jpg) | ![팀원](./image/team_psb.jpg) | ![팀원](./image/team_pyh.jpg) | ![팀원](./image/team_ywc.jpg) | ![팀원](./image/team_ljm.jpg) |
| 안드로이드, 빅데이터 | 안드로이드, 빅데이터, 픽셀아티스트 | 알림/서비스 API, 기록 확인 UI | 안드로이드, 빅데이터 | 서비스 API | CI/CD, 인증/인가 API |

<br/>

<h2> 4.2. 소스코드 </h2>

| 포지션 | URL to Readme |
| --- | --- |  
| 프론트앤드 | [gunpang-frontend](https://github.com/Gunpang-galaxy/gunpang-frontend/README.md) |  
| 백엔드 | [gunpang-backend](https://github.com/Gunpang-galaxy/gunpang-backend-public/blob/main/README.md) | 
| 빅데이터 | [gunpang-bigdata](https://github.com/Gunpang-galaxy/gunpang-bigdata/README.md) | 

<div align="center">
    <img src="./image/Banner_bottom.png" alt="Logo">
</div>


