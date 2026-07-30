<!-- Header Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=200&section=header&text=DONGWON%20LEE&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Finance%20%C3%97%20Data%20%C3%97%20AI%20Agents&descAlignY=60&descAlign=50" alt="header"/>
</p>

<!-- Social Badges -->
<p align="center">
  <a href="mailto:kik328288@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white" alt="Gmail"/></a>
</p>

---

## 🙋‍♂️ About Me

**금융 도메인의 데이터·AI 도구를 직접 만드는 학생 개발자입니다.**

웹·앱 풀스택 경험을 기반으로, 지금은 **금융 데이터 분석(DX)과 AI 에이전트(AX)** 에 집중하고 있습니다.
설계부터 구현까지 **AI 코딩 에이전트(Codex · Claude Code · MCP/Agents)를 적극 활용**해, 아이디어를 빠르게 동작하는 결과물로 만듭니다.

- 🎯 **Focus** — Finance × Data Analytics × AI Agents
- 🌱 **Edge** — 컴퓨터공학(주전공) × 응용통계학(복수전공) × 금융수학(추가이수)의 융합
- 🛠 **How I build** — AI 페어 프로그래밍으로 설계·구현·리뷰 사이클을 압축해, 혼자서도 아이디어를 끝까지 완성합니다

<br/>

## 🚀 Projects

> **저장소 이관 작업이 진행 중입니다.**
> 공개 준비가 끝난 저장소만 링크했고, 나머지는 이관 순서에 따라 링크를 추가할 예정입니다.
> 링크가 없는 항목도 실제로 진행한 작업이며, 아래 서술이 기여 내용입니다.

### 💰 금융 · 퀀트 · 데이터

**이스트소프트 AI 퀀트 4기** &nbsp;`2026` &nbsp;`부트캠프`
금융자산 지식을 서비스 형태로 서빙하는 시스템을 구축하는 과정. 과정 산출물을 **과제 · 작업일지 · 대시보드** 저장소로 나눠 정리하고, 투자 분석 파트는 별도 공개 저장소로 분리했습니다.
→ **[investment-analysis](https://github.com/EST-Bootcamp-Dongwon/investment-analysis)** &nbsp;`Public`
<sub>이 저장소는 과정에서 강사님이 Public으로 배포하신 학습용 프로젝트를 **허락받아** 학습·확장한 결과물입니다. 원본 커밋 히스토리를 보존했습니다.</sub>

**주식 분석 AI 에이전트** &nbsp;`팀 프로젝트` &nbsp;`Python`
16주 금융 부트캠프(BDAI PoCaT) **최종 팀 프로젝트**. 주식 분석과 투자 판단을 보조하는 AI 에이전트 파이프라인을 팀으로 구현했습니다.

**신용 위험 예측** &nbsp;`Python`
데이터 전처리부터 모델링까지, 신용 위험을 예측하는 파이프라인을 구성했습니다.

### 🌐 웹 · 앱

**Ember — 교환일기 기반 소개팅 앱** &nbsp;`팀 프로젝트` &nbsp;`Flutter` &nbsp;`Spring Boot`
2026-1 가천대학교 캡스톤디자인, 팀 **코드한조각(Code1piece)** 5인 프로젝트. 사진 대신 **일기**로 관계를 시작합니다. 기존 소개팅의 `외형 → 대화 → 내면` 순서를 **`내면 → 교환 → 외형`** 으로 뒤집어, AI가 일기 글에서 성향이 닮은 상대를 먼저 찾아주고 교환일기로 신뢰를 쌓은 뒤 프로필을 공개하는 구조입니다. KcELECTRA로 감정·생활·관계·톤 **33차원 태그**를 추출하고, KoSimCSE 코사인 유사도로 매칭 점수를 산출합니다.
**담당 (Backend)** — 사용자 인증, 매칭·교환일기 API, 데이터베이스 설계
→ 원본 팀 저장소 **[gc-code1piece/main](https://github.com/gc-code1piece/main)** &nbsp;`Public` · 개인 보관 사본 **[gc-dating-app](https://github.com/dev-dongwon05253/gc-dating-app)** &nbsp;`Public`
<sub>5인 공동 저작물이며, 원본에 라이선스 표기가 없어 재사용·재배포 권한은 부여되지 않습니다. 사본은 커밋 히스토리를 재작성하지 않고 그대로 보존했습니다.</sub>

**이모지 다이어리 — AI 감정 일기** &nbsp;`팀 프로젝트` &nbsp;`React` &nbsp;`Spring Boot` &nbsp;`Python`
2025-2 가천대학교 팀 프로젝트. 하루의 일기를 쓰면 **KoBERT** 가 본문을 분석해 7가지 감정(행복·중립·당황·슬픔·분노·불안·혐오)으로 분류하고, **Google Gemini** 가 그 감정에 맞춰 **그림일기·공감 코멘트·위로가 되는 음식**을 생성합니다. 코멘트는 사용자가 고른 페르소나(베프·부모님·전문가·멘토·상담사·시인)의 말투로 나오며, 쌓인 기록은 캘린더·타임라인·통계 차트로 되짚어볼 수 있습니다.
**담당** — 사용자 모바일 웹 화면 전반과 관리자 대시보드(서비스 통계·공지사항·시스템 설정·에러 로그), 백엔드·AI 서버 API 연동
→ 개인 보관 사본 **[Emoji-Diary](https://github.com/dev-dongwon05253/Emoji-Diary)** &nbsp;`Public`
<sub>팀 공동 저작물이며, 원본에 라이선스 표기가 없어 재사용·재배포 권한은 부여되지 않습니다. 사본은 보안을 위해 히스토리의 자격증명 문자열만 제거하고 나머지는 원본 그대로 보존했습니다.</sub>

**주식 포트폴리오 관리 웹 서비스** &nbsp;`JavaScript`
보유 종목과 수익률을 관리하는 웹 애플리케이션을 풀스택으로 구현했습니다.

### 🤖 AI 도구 · 자동화

**리서치 자동화** &nbsp;`G.I.C 동아리`
프롬프트 엔지니어링으로 반복적인 조사 업무를 단축했습니다.

**AI 카드뉴스 제작 도구** &nbsp;`TypeScript`
콘텐츠를 카드뉴스 형태로 자동 생성하는 도구를 풀스택으로 만들었습니다.

**Claude Code 활용 연구** &nbsp;`TypeScript`
MCP · Skills · Agents 활용법을 학습하고 정리했습니다.

<br/>

## 🛠 Tech Stack

**📊 Data / AI** &nbsp;`현재 집중`
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](#)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)](#)

**🔙 Backend**
[![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)](#)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)](#)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)](#)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)](#)

**🎨 Frontend**
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](#)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)](#)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)](#)

**💾 Database & Infra**
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)](#)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)](#)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)](#)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](#)

**🤖 AI Dev Tooling** &nbsp;`매일 사용`
[![OpenAI Codex](https://img.shields.io/badge/OpenAI%20Codex-412991?style=flat&logo=openai&logoColor=white)](#)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat&logo=anthropic&logoColor=white)](#)
[![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)](#)

<br/>

## 🎓 Education

**가천대학교 (Gachon University)** &nbsp;`2021.03 ~ 재학 중`

| 구분 | 전공 |
| :--- | :--- |
| 🖥️ 주전공 | 컴퓨터공학 |
| 📊 복수전공 | 응용통계학 |
| 💰 추가이수 (15학점+) | 금융수학부 빅데이터매니지먼트 |

<br/>

## 🏆 Certifications & Activities

**자격증** — SQLD (2025), ADsP (2024), 네트워크관리사 2급, ITQ OA, 정보처리기사(필기 합격)
<sub>한국데이터산업진흥원 · 한국정보통신자격협회 · 한국생산성본부 · 한국산업인력공단</sub>

| 활동 | 기간 | 역할 |
| :--- | :---: | :--- |
| **PLAF 1기** | `2026.03 ~` | AI Agent 스터디 |
| **BDAI 12기** | `2026 ~` | 빅데이터·AI 학술 소학회 |
| **G.I.C (IVY Club)** | `2025.06 ~` | 금융투자 동아리 |
| **CodeIn** | `2024.03 ~` | 중앙 코딩 동아리 |

<br/>

## 📫 Contact

<p>
  <a href="mailto:kik328288@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat&logo=gmail&logoColor=white" alt="Gmail"/></a>
</p>

<sub>📄 각 프로젝트의 라이선스와 사용 조건은 해당 저장소의 표기를 따릅니다.</sub>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=120&section=footer" alt="footer"/>
</p>
