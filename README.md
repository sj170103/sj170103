# Hello, I'm SJ!
> **Mobile & AI-Native Developer**  
> React Native, Kotlin으로 동작하는 앱을 만들고, LLM·AI 도구로 개발 효율을 끌어올리는 개발자입니다.  
> “실제 현장에서 돌아가는 서비스”를 목표로 꾸준히 공부하고 만들고 있습니다.

---

## 🚀 Key Projects

### 🏃 [RunTracker](https://github.com/sj170103/RunTracker-ReactNative)
**"Native 기술을 결합한 고성능 러닝 트래킹 앱"**  
백그라운드 위치 추적과 대용량 코스·이미지 렌더링을 최적화한 러닝 플랫폼입니다.

- **Role:** Mobile App & Native Module
- **Key Tech:** `React Native`, `TypeScript`, `Kotlin`, `Recoil`, `Skia`
- **Core Work & Achievements**
  - **Native Background Service**  
    React Native의 와 **Kotlin Foreground Service + Bridge**를 직접 구현해,  
    화면이 꺼지거나 앱이 백그라운드여도 **런닝중 끊김 없는 GPS 트래킹**을 달성했습니다.
  - **Rendering 최적화**  
    수천 개의 코스 좌표를 그릴 때 발생하는 **UI 스레드 블로킹**을  
    `InteractionManager`·지연 렌더링 전략으로 줄여, 실제 기기에서도 부드러운 지도를 구현했습니다.
  - **이미지·업로드 성능 개선**  
    `Skia/Canvas` 기반 커스텀 이미지 에디터를 만들고, 클라이언트에서 **WebP 변환**을 수행해  
    업로드 용량을 크게 줄이면서도 화면 품질을 유지했습니다.
  - **서비스 지향 설계**  
    러닝 기록·코스·피드·크루 기능을 고려한 도메인 구조와 상태 관리 패턴을 설계하고,  
    나중에 서버·배포를 붙일 수 있도록 API 레이어·타입 정의를 정리했습니다.

<br>

### ☁️ [근두운 (Geunduun)](https://github.com/sj170103/ak47-react-native)
**"위치 기반 흡연실 커뮤니티 & 지도 서비스"**  
Google Maps API 기반으로 흡연실 위치 정보와 사용자 커뮤니티 기능을 제공하는 LBS 앱입니다.

- **Role:** Frontend Lead & UI/UX
- **Key Tech:** `React Native`, `Google Maps API`
- **Core Work & Achievements**
  - **LBS 지도 기능**  
    사용자 현재 위치를 중심으로 흡연실/금연 구역을 마커로 시각화하고,  
    리스트·지도 전환, 마커 클릭 UX를 설계했습니다.
  - **커뮤니티 기능 설계**  
    장소 제보(CRUD), 리뷰·평점, 간단 통계 등을 담을 수 있는 화면·상태 구조를 설계하고,  
    실제 사용자 흐름을 고려한 입력 폼·피드 UI를 구현했습니다.
  - **초기 사이드 프로젝트**  
    이후 RunTracker 설계·UI/UX에 참고한, **첫 상용 지향 사이드 프로젝트**입니다.

<br>

### 🎤 [VocalAI · Voco](https://github.com/sj170103/vocalai)
**"AI 보컬 트레이닝 & 분석 엔진 + 모바일 코칭 앱"**  
사용자의 노래를 분석해 **발성·호흡·음정·리듬**을 평가하고, 연습 루틴까지 제안하는 프로젝트입니다.  
> **Backend:** `VocalAI` (AI/분석 엔진) · **Mobile App:** [Voco](https://github.com/sj170103/voco)  

> **[📄 개발 보고서 & 트러블슈팅 (Notion)](https://www.notion.so/AI-1f4f999c97c78016bfaec4421b3252db)**

- **Role:** AI Core Logic, Backend, Mobile 연동
- **Key Tech:** `Python`, `TensorFlow`, `Librosa`, `FastAPI`, `React Native (Expo)`
- **Core Work & Achievements**
  - **멀티모달 음성 분석 파이프라인**  
    단순 Pitch 감지 대신 **Mel-spectrogram, Chroma, RMS** 등 여러 특성을 결합한  
    멀티모달 딥러닝 모델을 설계하고, 전처리·특징 추출·모델 추론을 하나의 파이프라인으로 구성했습니다.
  - **데이터 품질·불균형 해결**  
    실제 녹음 데이터를 기준으로 노이즈·볼륨 편차를 분석하고,  
    **Audio Augmentation**으로 클래스 불균형을 줄여 모델의 일반화 성능을 개선했습니다.
  - **LLM 기반 피드백 & 연습 루틴**  
    분석 결과를 바탕으로 LLM을 사용해 사용자 친화적인 피드백 문장과  
    태그(예: Pitch, Breath, Rhythm)·연습 루틴을 자동 생성하는 구조를 설계했습니다.
  - **시각화 & 모바일 연동**  
    `matplotlib`로 점수·구간별 평가를 한눈에 볼 수 있는 대시보드 이미지를 생성하고,  
    이를 Voco 앱에서 히스토리/곡 상세 화면으로 보여주는 UX 플로우를 구성했습니다.

---

## 📚 Education & CS Foundation

### 💻 [SJ-CS](https://github.com/sj170103/sj-cs)
**"Codyssey SW Development Course Archive"**  
코디세이(Codyssey) 교육 과정에서 수행한 과제와 학습 내용을 정리한 저장소입니다.

- **Curriculum**
  - 자료구조·알고리즘
  - 네트워크·운영체제
  - Python·FastAPI 기반 백엔드 기초
- **Focus**
  - 과제 중심으로 **문제 정의 → 설계 → 구현 → 회고** 흐름을 반복하며  
    기초 CS 지식과 코드 구현 능력을 함께 다지는 데 집중했습니다.

---

## 🛠 Tech Stack

| Area | Stack |
| :--- | :--- |
| **Mobile & Native** | ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Expo](https://img.shields.io/badge/Expo-000000?style=flat&logo=expo&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) |
| **Backend & AI** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![Librosa](https://img.shields.io/badge/Librosa-000000?style=flat) |
| **AI Assist & Productivity** | ![ChatGPT](https://img.shields.io/badge/ChatGPT-74aa9c?style=flat&logo=openai&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlebard&logoColor=white) ![Perplexity](https://img.shields.io/badge/Perplexity-222222?style=flat&logo=perplexity&logoColor=white) ![Codex](https://img.shields.io/badge/Codex-000000?style=flat&logo=openai&logoColor=white) <br> `Gemini CLI` `Antigravity` |
| **Tools & Collaboration** | ![Recoil](https://img.shields.io/badge/Recoil-3578E5?style=flat&logo=recoil&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) |
| **Network & Etc. (Learning)** | TCP/IP, Routing, Subnetting, Basic Linux Networking Tools(ping, traceroute, tcpdump) |


---
