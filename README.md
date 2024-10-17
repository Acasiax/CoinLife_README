# 🪙 코인생활 - 가상자산 포트폴리오 앱
<img src="https://github.com/user-attachments/assets/b83d844d-8d4e-4ab2-9150-0ab7266f3346" alt="appstore" width="120" height="120">

## 프로젝트 소개
실시간 코인 시세부터 가상자산 포트폴리오 관리 까지 간편하게 할 수 있는 가상자산 포트폴리오 앱 입니다.
## 스크린샷
![코인생활-리드미-사진-001](https://github.com/user-attachments/assets/784c4f5e-e36b-4db7-a4b9-b77e87ed4dc3)

## 📱 시뮬레이션
| 검색 화면 | 자산 추가 화면 | 포트폴리오 화면 | 뉴스 화면 |
|---------------|---------------|---------------|---------------|
| <img src="https://github.com/user-attachments/assets/a041858d-f321-4ef8-8765-2609b20b9870" width="200" /> | <img src="https://github.com/user-attachments/assets/8a7c9fbb-680a-4a51-b7fb-a0c5b3f5048b" width="200" />> | <img src="https://github.com/user-attachments/assets/fe7c7c27-1d0b-4ed2-893d-b8c0830fb7b0" width="200" /> | <img src="https://github.com/user-attachments/assets/8eefd325-3de9-4bac-9310-9986492c4ff1" width="200" />

| 공포지수 화면 | 다크모드 설정 화면 | Face ID 화면 | 차트 화면 |
|---------------|---------------|---------------|---------------|
 | <img src="https://github.com/user-attachments/assets/fb10df48-839d-4575-938e-ff149e8104db" width="200" /> | <img src="https://github.com/user-attachments/assets/29cd6406-1488-4906-916d-1eaa071cd8f7" width="200" /> | <img src="https://github.com/user-attachments/assets/4a689071-147d-4c63-b650-5e6bda0f957d" width="200" /> | <img src="https://github.com/user-attachments/assets/e915434d-8e22-4c8a-bdee-9bdc68e2a32c" width="200" />



## ⚙️ 주요 기능

실시간 시세 반영: WebSocket을 이용한 실시간 코인 시세 확인<br/>
자산 검색: 사용자가 원하는 가상자산을 쉽게 검색 가능<br/>
실시간 수익률 분석: 사용자가 보유한 가상자산을 현 시세와 비교하여 실시간 수익률 분석 제공<br/>
다양한 차트 기능: 원형 차트, 막대 차트 등 다양한 차트를 통해 보유 자산 분포를 한눈에 시각화<br/>


## 💻 개발 환경

개발 기간: 2024년 9월 13일 ~ 2024년 10월 3일<br/>
개발 인원: 1명<br/>
개발 도구:<br/>
IDE: Xcode 15.4<br/>
버전 관리: Git<br/>

## 🛠️ 기술 스택
UI: SwiftUI – 제약 조건 기반 인터페이스 구성<br/>
네트워크: Alamofire – Upbit API, WebSocket 및 Naver News API와의 네트워크 통신<br/>
데이터베이스: RealmSwift – 사용자의 보유 자산 데이터를 안전하게 저장<br/>
Reactive Programming: RxSwift, RxCocoa – 반응형 데이터 처리 및 이벤트 바인딩<br/>

## 📁 디렉토링 구조
```
MyCoinPoket
├── Application
│   ├── AppDelegate.swift
│   └── SceneDelegate.swift
├── Base.lproj
│   └── LaunchScreen.storyboard
├── Global
│   ├── Components
│   ├── Extensions
│   ├── Protocols
│   ├── Realm
│   └── Resources
├── Info.plist
├── Network
│   ├── Base
│   ├── Credits
│   ├── Genre
│   ├── NetworkManager.swift
│   ├── Search
│   ├── Similar
│   └── Trending
└── Presentation
    ├── Base
    ├── TrendingView
    ├── Splash
    ├── SettingListView
    ├── FeedandGreedRefact
    ├── GptView
    ├── AddCoinView
    ├── SoketNetwork
    ├── MainCoinView
    └── NaverNewsScrollView


```

## 🤔 고민한 부분



## 😨 트러블 슈팅

