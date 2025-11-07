# 📜 DreamsComeTrue
> 게임처럼 즐기는 투두리스트 앱  
> 매일의 할 일을 퀘스트처럼 수행하고, 경험치와 보상을 모아 성장하는 **게이미피케이션형 생산성 앱**

---

## 🏠 프로젝트 개요

| 항목 | 내용 |
|------|------|
| **프로젝트명** | DreamsComeTrue |
| **개발 형태** | 팀 프로젝트 (2인 개발) |
| **개발 목적** | 투두리스트의 ‘지속성’ 문제를 게임적 재미로 해결 |
| **주요 특징** | 퀘스트 / 출석 / 경험치 / 캘린더 / 수집요소 |
| **개발 환경** | Android Studio / Expo (React Native) ***[미정]*** |
| **목표 플랫폼** | Android 모바일 앱 |

---

## 🎯 주요 기능

| 기능 | 설명 |
|------|------|
| 🪵 **퀘스트 게시판** | 매일의 할 일을 퀘스트로 등록, 상태(미완료/진행중/완료됨) 관리 |
| 🧙‍♂️ **레벨 시스템** | 완료한 퀘스트로 경험치 획득, 레벨 상승 |
| 📆 **캘린더 연동** | 날짜별 수행 기록 및 미션 달성률 시각화 |
| 🎁 **보상 & 수집 요소** | 출석체크, 랜덤 보상, 수집형 요소로 동기 부여 |
| ⚙️ **개발자(Dev) 메뉴** | 테스트용 데이터 초기화 및 통계 확인 기능 |
| 🕹️ **pvp 요소** | 레벨별 스탯업으로 원하는 타입의 캐릭터 만들기 |

---

## 🧩 기술 스택

| 분야 | 사용 기술 |
|------|------------|
| **Frontend** | React Native (Expo) / TypeScript ***[미정]*** |
| **Backend** | Firebase (Auth, Firestore, Storage) ***[미정]*** |
| **Design** | Figma / PixelArt / Tailwind-style concept ***[미정]*** |
| **Tools** | Git / GitHub / Android Studio / VSCode ***[미정]*** |

---

## 📱 앱 구조 (예정) ***[예시]***

```plaintext
DreamsComeTrue/
 ├─ assets/         # 이미지, 아이콘
 ├─ components/     # 공용 컴포넌트 (Header, QuestCard 등)
 ├─ screens/        # 주요 화면 (Home, QuestBoard, Stats 등)
 ├─ hooks/          # 커스텀 훅
 ├─ utils/          # 유틸 함수, 날짜 처리 등
 ├─ App.tsx         # 메인 진입점
 └─ README.md
```

---

## 🎨 디자인 컨셉 (예정) ***[예시]***

- **메인 컬러:** `#AAFAFF`  
- **테마:** 따뜻한 마을 느낌의 ‘퀘스트보드 + 플레이어 캐릭터’  
- **UI 포인트:** 나무 게시판, 퀘스트 종이, 손그림 아이콘 or 픽셀 아이콘

---

## 👥 팀 구성

| 이름 | 역할 | GitHub |
|------|------|--------|
| 🧑‍💻 **yeoning** | 기획 · 메인 로직 · UI 설계 | [@yeoning22](https://github.com/yeoning22) |
| 👩‍💻 **익명** | 보조 개발 · 디자인 · 테스트 | (없음) |

---

## 🚀 설치 및 실행 (예정)

```bash
# Clone Repository
git clone https://github.com/yeoning22/dreamscometrue.git

# Install dependencies
npm install

# Run (Expo)
npx expo start
```

---

## 🧭 로드맵

- [ ] 페이지 별 디자인  
- [ ] 기본 퀘스트 등록 / 완료 기능  
- [ ] 경험치 시스템  
- [ ] UI 개편 (퀘스트보드, 출석체크)  
- [ ] Firebase 연동  
- [ ] 수집 요소 / 캐릭터 성장
- [ ] 상점 시스템 / 스텟 분배 기능
- [ ] Google Play 배포  

---

## ⚖️ 라이선스

이 프로젝트는 [MIT License](./LICENSE)를 따릅니다.  
자유롭게 수정·배포 가능하며, 출처 표시를 권장합니다.

---

## 💬 기타

> “팀 모토.”  
> — *미정 팀*
> 
> “단 한번의 성공보단 꾸준한 노력이 중요하다.”  
> — *yeoning*
> 
> “한 줄 메세지.”  
> — *익명*
