<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="./assets/banner.svg" width="100%" alt="worksenddl2 — Physical AI × CPTED Developer" />

<a href="https://github.com/worksenddl2-source"><img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" /></a><a href="https://github.com/worksenddl2-source"><img src="https://img.shields.io/badge/WORKSENDDL2--SOURCE-4FD1FF?style=for-the-badge" /></a>
<img src="https://img.shields.io/badge/FOCUS-1B2550?style=for-the-badge" /><img src="https://img.shields.io/badge/PHYSICAL%20AI%20×%20CPTED-FFD43B?style=for-the-badge" />

</div>

---

## About Me — 어떤 개발자인가

> **범죄가 일어난 뒤 쫓는 기술이 아니라, 범죄가 일어나기 전에 막는 기술을 만들고 싶습니다.**

**CPTED(셉테드, 범죄예방 환경설계)** 는 조명·시야·동선 같은 *환경*을 설계해 범죄 기회를 줄이는 기법입니다.
저는 여기에 **피지컬 AI**, 즉 *보고(카메라) · 판단하고(AI) · 움직이는(하드웨어)* 기술을 더해
**환경이 스스로 위험을 감지하고 반응하는 공간**을 만드는 개발자가 되는 것이 목표입니다.

```python
class CPTEDxPhysicalAI:
    def __init__(self):
        self.name   = "worksenddl2"
        self.role   = "Physical AI × CPTED Developer"
        self.dream  = "AI가 지켜보고, 환경이 반응해, 범죄가 일어나지 않는 거리"
        self.now    = ["Computer Vision", "Arduino", "Physical AI Project"]

    def pipeline(self):
        return ["SEE", "DETECT", "LIGHT UP", "PREVENT"]
```

| CPTED 원리 | 피지컬 AI로 구현하고 싶은 것 |
| :--- | :--- |
| **자연적 감시** (보이는 거리) | 비전 AI가 사각지대의 사람·이상행동을 실시간 감지 |
| **영역성·활동 지원** (밝고 활기찬 공간) | 사람이 지나가면 반응하는 스마트 조명·센서 |
| **접근 통제** (위험 구역 관리) | 제스처·자세 인식으로 구조요청 신호를 자동 감지 |
| **유지관리** (깨진 유리창 방지) | 고장난 조명·시설물을 데이터로 찾아내는 모니터링 |

- **피지컬 AI 팀 프로젝트**에서 Python 비전 AI와 아두이노 하드웨어를 직접 다루고 있습니다.
- 지금 만드는 프로젝트들은 모두 **CPTED × 피지컬 AI라는 꿈으로 가기 위한 학습 과정**입니다.

<a href="./docs/cpted-physical-ai.md"><img src="https://img.shields.io/badge/READ-CPTED%20%C3%97%20Physical%20AI%20%EA%B5%AC%EC%83%81%20%EB%85%B8%ED%8A%B8-FFD43B?style=for-the-badge&labelColor=1B2550" alt="CPTED × Physical AI 구상 노트" /></a>

---

## Projects — 꿈으로 가는 학습 과정

> 아래 프로젝트들은 **CPTED × 피지컬 AI**를 접목하기 전, 필요한 기술을 하나씩 익히고 있는 **학습 단계의 결과물**입니다.

<div align="center">

| Project | Description | 꿈과의 연결 | Stack |
| :--- | :--- | :--- | :---: |
| **Physical AI Project** | 피지컬 AI 팀 프로젝트 *(진행 중)* | 카메라·AI·하드웨어를 하나의 시스템으로 통합 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Physical%20AI](https://img.shields.io/badge/-Physical%20AI-76B900?style=flat-square) |
| [**YOLO26 Webcam**](https://github.com/worksenddl2-source/yolo26-webcam) | Ultralytics YOLO26으로 웹캠 실시간 객체 탐지 & 세그멘테이션 | CCTV 속 사람·물체 실시간 감지 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![YOLO](https://img.shields.io/badge/-YOLO-111F68?style=flat-square) ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| [**MediaPipe Vision Webcam**](https://github.com/worksenddl2-source/mediapipe-vision-webcam) | 손 제스처·얼굴 랜드마크 인식, 커스텀 제스처 데이터 수집·학습(scikit-learn) | 손짓·자세로 위급 신호 인식 | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MediaPipe](https://img.shields.io/badge/-MediaPipe-0097A7?style=flat-square&logo=mediapipe&logoColor=white) ![scikit--learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| [**Arduino Uno Practice**](https://github.com/worksenddl2-source/arduino-uno-practice) | LED·버튼·인터럽트·PWM·네오픽셀 제어 등 16종 회로 구현 | 센서 반응형 스마트 조명 제어 | ![C%2B%2B](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00878F?style=flat-square&logo=arduino&logoColor=white) |
| [**Orca Electric**](https://github.com/worksenddl2-source/orca-electric) | 전자부품 쇼핑몰 풀스택 구현 (DB·인증·결제) | 감지 결과를 보여줄 웹 대시보드 구현 역량 | ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Toss%20Payments](https://img.shields.io/badge/-Toss%20Payments-0064FF?style=flat-square) |

<a href="https://github.com/worksenddl2-source?tab=repositories">
  <img src="https://img.shields.io/badge/All%20Repositories-1F4E79?style=for-the-badge" />
</a>

</div>

---

## Tech Stack — 직접 다뤄 본 기술

**Language**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B" />
<img src="https://img.shields.io/badge/C%2B%2B%20(Arduino)-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />

**AI / Computer Vision**<br/>
<img src="https://img.shields.io/badge/YOLO%20(Ultralytics)-111F68?style=for-the-badge&logo=ultralytics&logoColor=white" />
<img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=mediapipe&logoColor=white" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
<img src="https://img.shields.io/badge/Teachable%20Machine-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />

**Embedded / Hardware**<br/>
<img src="https://img.shields.io/badge/Arduino%20Uno-00878F?style=for-the-badge&logo=arduino&logoColor=white" />
<img src="https://img.shields.io/badge/NeoPixel-8E44AD?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Wokwi%20Simulator-2E7D32?style=for-the-badge&logoColor=white" />

**Web / Backend**<br/>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/Toss%20Payments-0064FF?style=for-the-badge&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />

**Environment & Tools**<br/>
<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />

---

<!-- ===================== FOOTER ===================== -->
<div align="center">

**“AI가 지켜보고, 환경이 반응해, 범죄가 일어나지 않는 거리를 만든다.”**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E1F4F,50:1B2550,100:0B1026&height=120&section=footer" width="100%" />

</div>
