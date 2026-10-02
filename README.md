# 🎮 Unity Rock-Paper-Scissors (가위바위보 게임)

유니티(Unity)와 TextMeshPro를 활용하여 제작한 2D 가위바위보 게임 프로젝트입니다.

---

## 🛠️ 개발 환경 (Development Environment)
* **Engine**: Unity
* **UI Framework**: TextMeshPro (TMP)
* **Language**: C#

---

## 🕹️ 주요 기능 (Main Features)
* **가위바위보 선택**: 플레이어가 가위, 바위, 보 버튼 중 하나를 선택하면 컴퓨터가 랜덤으로 선택하여 승패를 판정합니다.
* **점수 시스템**: 승리 및 패배에 따라 실시간으로 점수(`Score_User`, `Score_Computer`)가 누적됩니다.
* **게임 오버 및 리셋**: 특정 점수에 도달하면 결과 패널(`Panel_Result`)이 활성화되며, 게임을 다시 시작하거나 종료할 수 있습니다.

---

## 📁 프로젝트 구조 (Project Structure)
```text
Rock_Paper_Scissors/
├── Assets/
│   ├── Animation/      # 버튼 및 UI 애니메이션 제어
│   ├── Fonts/          # NanumGothic 폰트 및 TMP Font Asset
│   └── Scenes/         # 메인 게임 씬 (SampleScene)
├── Packages/           # 패키지 매니저 설정
└── ProjectSettings/    # 유니티 프로젝트 설정