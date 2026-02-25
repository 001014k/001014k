<!-- 헤더 배너 -->
![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&animation=fadeIn&section=footer&text=👨🏻‍💻)

<!-- 방문자 배지 추가 -->
<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=001014k.001014k" />
</p>

<!-- GitHub Stats -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=001014k&layout=compact&theme=blue_navy" />
  <img src="https://github-readme-stats.vercel.app/api?username=001014k&show_icons=true&hide=contribs,prs&cache_seconds=86400&theme=blue_navy" />
</p>

---

## 👋 안녕하세요, Flutter 중심 모바일 개발자 김명종입니다!

React와 Flutter를 활용한 크로스플랫폼 앱·웹 개발자입니다.  
**사용자 친화적인 UI/UX**와 **클린 아키텍처(MVVM)**를 기반으로 효율적이고 확장성 높은 앱을 설계·구현하는 데 집중합니다.

현재 가장 공들인 프로젝트는 **TripNest** – 여행 메모·플래너 앱으로,  
지도 기반 마커 관리, Supabase Realtime을 활용한 실시간 친구 협업, 다중 네비게이션(Google·Kakao·Naver Maps) 연동, 외부 링크(Instagram·YouTube) 저장 기능을 핵심으로 합니다.  
Gemini AI 기반 장소 추천 기능도 개발 중이며, TestFlight를 통해 베타 배포 중입니다 (링크: https://testflight.apple.com/join/wP415NqW).

**백엔드 선택과 전환 경험**  
프로젝트 초반에는 Firebase(Firestore + Authentication)를 사용해 빠르게 프로토타이핑을 진행했습니다.  
하지만 여행 리스트·마커·친구 관계 등 **관계형 데이터**가 많아지면서 NoSQL 문서 구조의 한계(테이블 같은 명확한 스키마 부족, 복잡한 조인·데이터 흐름 파악 어려움)를 느꼈습니다.  
이에 **데이터 관리와 쿼리 효율성**을 높이기 위해 Supabase(PostgreSQL 기반 관계형 DB)로 전환했습니다.  
전환 후 Supabase Realtime으로 실시간 동시 편집·공유를 구현하고, SQL 테이블 설계로 데이터 일관성과 쿼리 성능을 크게 개선할 수 있었습니다.  
이 과정에서 NoSQL과 SQL의 장단점을 직접 비교·적용하며 백엔드 선택 기준을 깊이 고민하게 되었습니다.

주요 강점과 경험:
- **실시간 데이터 동기화** : Supabase Realtime으로 친구와 동시에 여행 리스트 편집·공유
- **지도 & 마커 기능** : 마커 등록·삭제·클러스터링, 북마크, 클릭 시 원하는 지도 앱 길찾기
- **백엔드 연동** : Firebase(초기 인증·호스팅) → Supabase(메인 DB·Realtime) 병행/전환 경험
- **CI/CD 자동화** : Jenkins 파이프라인 구축 + Fastlane으로 iOS TestFlight 배포 자동화 → 릴리즈 속도 향상 및 오류 최소화
- **성능 최적화** : cached_network_image로 스크롤 플리커링 제거, const 위젯·캐싱 활용
- **크로스플랫폼** : Android·iOS·Web·Desktop 지원, 총 475회 커밋 (2026년 2월 기준 활발 진행 중)

Provider 기반 상태 관리 경험을 바탕으로 데이터 흐름의 안정성을 높였으며,  
커스텀 UI·리스트·마커 등 실제 서비스 수준 기능을 직접 설계·구현해왔습니다.

문제 인식부터 해결까지 주도적으로 경험하며 성장하고, 팀 협업으로 더 나은 사용자 경험을 만드는 개발자가 되고자 합니다. 🚀

---

## 📁 프로젝트 소개

| 프로젝트명 | 설명 | 사용 기술 | 링크 |
|------------|------|-----------|------|
| 🗺️ TripNest | Supabase 기반의 여행지 마커 앱 (지도, 북마크, 친구 기능 포함) | <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white"/> <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/> <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Google_Maps-4285F4?style=flat&logo=googlemaps&logoColor=white"/> | [<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>](https://github.com/001014k/TripNest) - 📱 개발중 |
| 🛒 중고 장터 경매 시스템 | 실시간 입찰, 거래, 채팅 기능을 포함한 중고 거래 플랫폼 | <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white"/> <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black"/> | [<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>](https://github.com/001014k/trading-platform) |
| 🏙️ Terra | 상권 추천 서비스 (실시간 데이터 기반 상권 분석 및 추천) |  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white"/> <img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white"/> <img src="https://img.shields.io/badge/Mapbox-000000?style=flat&logo=mapbox&logoColor=white"/> | [<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>](https://github.com/Pianuu999/Terra) - 협업 작품 |

---

## 📌 프로젝트별 역할 및 기여

### 🗺️ TripNest
- Flutter 기반 MVVM 구조 설계 및 전체 앱 UI 구현
- Supabase 기반 실시간 친구 초대 및 일정 공유 로직 구현
- 지도 마커 등록/삭제, 클러스터링, 북마크 기능 개발
- SNS/웹 공유 링크를 참조 자료 또는 마커로 저장하는 기능 설계

### 🛒 중고 장터 경매 시스템
- 실시간 입찰 기능 설계 및 Firebase 연동
- 실시간 데이터베이스를 활용한 입찰 UI 구현
- 사용자 인증 및 채팅 흐름 기획

### 🏙️ Terra
- 공공데이터 기반 유동인구 및 상권 정보 수집 및 시각화
- Mapbox 지도 시각화 및 JSON 파싱 처리
- 상권 추천 로직 설계 및 UI 반영

---

## 🛠️ 프로젝트별 개발 도구

| 프로젝트명 | 개발 도구 |
|------------|------------|
| 🗺️ TripNest | <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=flat&logo=android-studio&logoColor=white"/> <img src="https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white"/> <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white"/> |
| 🛒 중고 장터 경매 시스템 | <img src="https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat&logo=android-studio&logoColor=white"/> <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white"/> |
| 🏙️ Terra | <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat&logo=intellij-idea&logoColor=white"/> <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white"/> |

---

## 📦 프로젝트별 GitHub Repo Cards

<div align="center">

<a href="https://github.com/001014k/TripNest" target="_blank">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=001014k&repo=TripNest&theme=blue_navy" alt="TripNest Repo Card" style="margin: 10px;" />
</a>

<a href="https://github.com/001014k/trading-platform" target="_blank">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=001014k&repo=trading-platform&theme=blue_navy" alt="Trading Platform Repo Card" style="margin: 10px;" />
</a>

<a href="https://github.com/Pianuu999/Terra" target="_blank">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Pianuu999&repo=Terra&theme=blue_navy" alt="Terra Repo Card" style="margin: 10px;" />
</a>

</div>

---

## 🛠️ 사용 기술 (Tech Stack)

<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" />
</p>

---

## 🧰 개발 도구 (Tools)

<p align="left">
  <img src="https://img.shields.io/badge/VS Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white" />
  <img src="https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
</p>

---

## 💪 개인 기술 스택 (Skills & Expertise)


### 📱 모바일 앱 개발  
Flutter, Dart, Kotlin, Android, iOS 등 모바일 앱 개발 역량

<p align="left" style="margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" alt="Flutter" />


### 🌐 웹 개발  
React, JavaScript 기반 웹 개발 경험

<p align="left" style="margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
</p>


### 🗄️ 백엔드 & DB  
Supabase, Firebase 등 백엔드 및 데이터베이스 활용 능력

<p align="left" style="margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase" />
</p>


### 🔧 버전 관리 및 협업 도구  
Git, GitHub 등 협업과 버전관리 도구 사용 경험

<p align="left" style="margin-bottom: 20px;">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" />
</p>



---

<h3 align="center">💡 "기술은 사람을 연결하는 다리입니다"</h3>
