![header](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&text=Welcome%20to%20Eunah's%20GitHub%20👋&animation=twinkling&fontSize=35&fontAlignY=40&fontAlign=70&height=250)

# 안녕하세요! 👋

### 모델 설계부터 서비스 운영까지, End-to-End AI 개발자 정은아입니다.

- 통계학 석사로서 데이터에 대한 깊은 이해를 바탕으로 문제를 정의하고, 실제 서비스 환경까지 고려한 AI 모델을 개발하는 데 집중하고 있습니다.
- 딥러닝 기반의 새로운 모델 구조를 직접 제안하고 구현하는 도전을 즐기며, 데이터 수집부터 최적화, API 연동까지 AI 개발의 전 과정을 주도한 경험이 있습니다.
- 복잡한 문제를 해결하고 동료와 함께 성장하는 과정에서 큰 보람을 느낍니다.

<br>


### 🎓 Education
---
- **중앙대학교 대학원** (2022.03 - 2024.02)
    - 통계데이터사이언스학과 통계학 석사 (GPA: 3.84/4.5)
    - *졸업 논문: 3D Pulmonary Nodule Segmentation Network with Self-Supervised learning and Attention Mechanism*
- **한국외국어대학교** (2018.03 - 2022.02)
    - 경영학 학사 / 통계학 이학사 (복수전공) (GPA: 4.05/4.5)
    - *졸업 논문: 데이터 마이닝을 이용한 CRM(고객 관계 관리) - 고객 스코어링 방법을 활용한 정기예금 상품 신규 가입 타겟 모델 구축*

<br>

### 💻 Experience & Activities
---
- **삼성 청년 SW 아카데미 (SSAFY) 12기** (2024.07 - 2025.06)
    - 기업 연계 프로젝트 우수상 수상 (2025.06)
    - 웹 기술 스택 및 AI 모델 서비스 연동 구조 설계 경험 습득
- **중앙대학교 인공지능 연구실 (AI STAT LAB) 연구원** (2022.03 - 2024.02)
    - 딥러닝 기반 3D 의료 영상 분할 모델 연구 주도
    - 자기 지도 학습과 어텐션 메커니즘을 결합한 신규 모델 제안 및 구현
    - **[[Link](https://sites.google.com/view/cwlim/home?authuser=0)]** 


<br>



### 🛠️ Tech Stack
---
**AI/ML** <br>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/> <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>

**Backend & Database** <br>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>

**Infra & DevOps** <br>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>

**Collaboration** <br>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>

<br>

### 🚀 Projects

---

### 🏆 시시각각 (Sisi-Guard) - 무인매장 실시간 AI 보안 시스템 (기업 연계 프로젝트 우수상)

*실시간 CCTV 영상 스트림을 분석하여 도난, 설비 훼손 등 이상행동을 탐지하고 알림을 전송하는 서비스*

- **역할:** 팀장, AI 리드
- **주요 기여:**
    - VLM 분석과 이벤트 클립 생성을 연계한 **자체 순환형 데이터 파이프라인** 설계
    - 모션 감지, YOLOv5, SSIM 유사도 분석을 결합한 **프레임 필터링 전략**으로 VLM 연산량 최적화
  - RTSP 스트림 데이터 자체 수집 및 FastAPI 기반 추론 서버 구축
  <details>
    <summary>
    <b>[ 펼쳐보기 ] End-to-End AI 개발 프로세스별 경험 상세</b></summary>
    <br>

    *본 프로젝트는 실제 서비스 환경을 가정한 **데이터 파이프라인 구축, 실시간 API 연동, 리소스 최적화**에 중점을 둔 경험입니다.*

    - **1. 데이터 수집:** PoE 허브와 IP 카메라에서 **RTSP 스트리밍**으로 Full-HD 영상을 실시간으로 직접 수집했습니다.

    - **3. 데이터 파이프라인 구축:** VLM 1차 분석 → 이상행동 클립 생성 → VLM 2차 심층 분석으로 이어지는 **자체 순환형 데이터 파이프라인**을 설계하여 '신속성'과 '분석 품질'을 모두 확보했습니다.

    - **4. 모델 설계/선택:** Vision-Language Model(VLM)을 채택하고, 연산량 최소화를 위해 **모션 감지 + YOLOv5 + SSIM 유사도 분석**을 결합한 다단계 **프레임 필터링** 로직을 설계했습니다.

    - **7. 최적화:** 모든 프레임을 분석하며 발생하는 병목 현상을 해결하기 위해, 이상 행동일 확률이 높은 중요 프레임만 선별하여 분석하는 방식으로 **연산 리소스를 최적화**했습니다.

    - **8. API 서비스 연동:** **FastAPI**로 구축된 추론 서버의 분석 결과를 백엔드 서버로 실시간 전송하는 API를 개발하여 서비스 연동을 완료했습니다.

  </details>
- **기술 스택:** `Python`, `FastAPI`, `YOLOv5`, `Docker`, `AWS EC2`, `Jenkins`, `Git`, `Jira`
- **[[Repository](https://github.com/s1-guard)]** 
 

<hr>

### 🚕 도로로 (DOROLAW) - AI 기반 교통사고 과실비율 산정 서비스

*블랙박스 영상 분석을 통해 교통사고 유형을 분류하고 과실 비율을 산정하는 서비스*

- **역할:** AI 리드
- **주요 기여:**
    - **Zero-shot 스크리닝** 실험을 통해 학습 전 최적 모델(TSN)을 효율적으로 선정
    - 데이터 병목 현상 해결을 위해 배치 사이즈, 워커 수 등을 조정하여 **GPU 활용률 최적화**
    - Kinetics-400 사전 학습 모델을 활용한 **전이 학습** 및 다양한 학습 전략(스케줄러, 데이터 증강 등) 적용으로 성능 향상
    <details>
    <summary>
    <b>[ 펼쳐보기 ] End-to-End AI 개발 프로세스별 경험 상세</b></summary>

    *본 프로젝트는 제한된 리소스 하에서 **최적 모델을 효율적으로 탐색**하고 **GPU 성능을 극한으로 활용**하며 모델 성능을 높이는 데 강점이 있는 경험입니다.*

  - **2. 데이터 전처리:** 비디오당 8개 프레임 샘플링, 무작위 자르기, 좌우 반전 등 다양한 **데이터 증강 및 전처리** 기법을 적용했습니다.

  - **4. 모델 설계/선택:** 학습 리소스 제약 하에 **Zero-shot 스크리닝** 실험을 통해 여러 후보군 중 TSN을 최종 모델로 합리적으로 선정했습니다.

  - **5. 학습 및 튜닝:** Kinetics-400 데이터셋으로 **전이 학습**을 진행하고, Linear Warmup & Cosine Annealing 스케줄러 등 다양한 **하이퍼파라미터 튜닝** 전략을 적용했습니다.

  - **7. 최적화:** 데이터 로딩 병목 현상 해결을 위해 배치 사이즈와 CPU 워커 수를 조정하여 **GPU 활용률을 최적화**했습니다.

  </details>
    
- **기술 스택:** `Python`, `PyTorch`, `TSN`, `YOLOv8`, `Kinetics-400`, `Jupyter Lab`
- **[[Repository](https://github.com/eunah320/dorolaw-project)]** 


---

### 🫁 3D CT 이미지 폐 결절 분할 AI 모델 개발 (정부 지원 연구 과제: 과학기술정보통신부: NRF-2021R1F1A1056516, 석사 학위 논문)

*자기 지도 학습(Self-Supervised Learning)과 어텐션 메커니즘을 활용한 3D 폐 결절 분할(Segmentation) 네트워크*

- **역할:** 단독 연구 및 개발
- **주요 기여:**
    - 라벨링된 의료 데이터 부족 문제를 해결하기 위해 **자기 지도 학습 기반의 새로운 모델 아키텍처** 직접 제안 및 구현
    - Ablation Study를 통해 제안한 **어텐션 모듈과 자기 지도 학습의 효과를 정량적으로 검증**
    - 3D 데이터의 구조적 복잡성을 해결하고 기존 모델 대비 **성능 향상 (CPM 0.019↑)** 달성
    <details>
    <summary>
    <b>[ 펼쳐보기 ] End-to-End AI 개발 프로세스별 경험 상세</b></summary>
    
    *본 프로젝트는 기존 모델의 한계를 극복하기 위해 **새로운 모델 아키텍처를 직접 제안**하고, **Ablation Study**를 통해 유효성을 스스로 검증하는 깊이 있는 연구 역량을 보여줍니다.*

    - **2. 데이터 전처리:** 의료 영상 데이터의 특성을 고려하여 1x1x1mm 리샘플링, 3D 폐 분할 마스크 생성 등 전문적인 전처리 과정을 수행했습니다.

    - **4. 모델 설계/선택:** 라벨링 데이터 부족 문제를 해결하기 위해 **자기 지도 학습(Self-Supervised Learning)**과 3D 데이터의 복잡성 극복을 위한 **어텐션 메커니즘**을 결합한 **새로운 3D Segmentation 모델 구조를 직접 제안 및 설계**했습니다.

    - **6. 성능 평가:** **Ablation Study(절제 연구)**를 통해 제안한 구성 요소들이 모델 성능에 미치는 영향을 정량적으로 철저하게 검증했습니다.

  </details>
- **기술 스택:** `Python`, `PyTorch`, `3D U-Net`, `Self-Supervised Learning`, `Attention Mechanism`
- **[[논문 링크](https://www.riss.kr/link?id=T16954590)]** 

---

### 🏦 데이터 마이닝 기반 정기예금 신규 가입 타겟 모델 구축 (학사 학위 논문)

*데이터 마이닝의 고객 스코어링 기법을 활용, 은행의 정기예금 상품 가입 가능성이 높은 고객을 예측하여 타겟 마케팅 효율을 높이는 모델 개발*

- **역할:** 단독 연구 및 개발
- **주요 기여:**
    - UCI Bank Marketing 데이터를 활용하여 고객의 상품 가입 확률을 예측하는 **스코어카드 모델** 설계
    - **로지스틱 회귀분석**을 적용하고, K-S 통계량(0.27) 및 PSI(0.0018) 지표를 통해 모델의 **예측력과 안정성을 검증**
    - 데이터 기반의 효율적인 마케팅 전략 수립 가능성 제시
- **기술 스택:** `R`, `scorecard`, `creditmodel`, `ggplot2`


<br>


### 📫 Contact & Channels
---
- **Email:** [eunah320@gmail.com](mailto:eunah320@gmail.com)

<br>


