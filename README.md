<div align="center">

# 안녕하세요, 유주형입니다 👋

### 생명과학의 질문들을 통계, 모델링, 실험으로 풀어냅니다.

</div>

---

## 👋 About

- 🧬 **서울대 항체·면역학 연구실 학부연구생** — AlphaFold3 계열 구조 예측 모델이 항체–항원 도킹에서 MSA에 의한 편향을 찾고, 해소하는 방법론을 연구했습니다.
- 🧫 **고려대 RNA 대사 및 세포 신호 전달 연구실 학부연구생** — mTORC1 중심의 암세포 신호 전달, 종양 미세 환경을 위한 단백질, mRNA 정량 실험 및 연구를 했습니다.
- 💊 **데이터사이언스 학회 투빅스(ToBig's) 25·26기 프로젝트** — 25기 운영 부장으로 동아리를 이끌었습니다. 1) 25기 컨퍼런스에서 CV+OCR+LLM 복약지도 시스템 **PILLAR**에서 PM 및 Late-Fusion 단계를 수행했습니다. 2) 26기 컨퍼런스에서 ADMET 22종 예측 모델에서 입력 서열의 특성에 따른 불안정성 정량 플랫폼 **SENSE**에서 PM 역할을 수행했습니다.
- 📊 **FNC entertainment 산학 연구 프로젝트** — 기획 의도와 팬 반응 사이의 괴리도 측정 플랫폼을 제작했습니다. 유튜브 댓글 데이터 수집부터 모델 학습, 웹 데모 배포까지 완료했습니다.

---

## 🛠 Tech Stack

**Language**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**ML / DL**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Computer Vision**

![Ultralytics YOLO](https://img.shields.io/badge/Ultralytics_YOLO-111F68?style=for-the-badge&logo=yolo&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B0?style=for-the-badge&logo=paddlepaddle&logoColor=white)

**NLP / LLM**

![OpenAI-compatible API](https://img.shields.io/badge/OpenAI--compatible_API-412991?style=for-the-badge)
![Upstage Solar](https://img.shields.io/badge/Upstage_Solar-7C3AED?style=for-the-badge)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Data / Infra**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

**Bio / Structure**

![AlphaFold3](https://img.shields.io/badge/AlphaFold3-1A73E8?style=for-the-badge&logo=deepmind&logoColor=white)
![Boltz-2](https://img.shields.io/badge/Boltz--2-0B7285?style=for-the-badge)
![Protenix](https://img.shields.io/badge/Protenix-2B8A3E?style=for-the-badge)
![HADDOCK](https://img.shields.io/badge/HADDOCK-A61E4D?style=for-the-badge)
![Biopython](https://img.shields.io/badge/Biopython-3776AB?style=for-the-badge&logo=biolink&logoColor=white)

---

## 🚀 Projects

### 🩺 PILLAR — AI 복약 지도 자동 생성 시스템

`Team PM` · 투빅스 25기 컨퍼런스 · **[Feellived/Pillar](https://github.com/Feellived/Pillar)**

여러 약을 함께 먹는 다약제 복용 환경에서, 약봉투를 잃어버리는 순간 “무슨 약인지” 확인할 방법이 사라진다는 문제에서 출발했습니다. 알약 사진 한 장으로 약을 식별하고 상호작용까지 짚어주는 파이프라인을 설계했습니다.

```
사진 → YOLOv11n 검출 → [ConvNeXt 색·모양 분류기 ∥ PaddleOCR 각인 인식]
     → 학습된 Late Fusion(조건부 로짓) → Top-3 후보 → 사용자 확인
     → DUR DB 병용금기 검색 → LLM 복약지도서 생성
```

- **Learned Late Fusion** — 두 신호를 규칙이 아니라 조건부 로짓 최적화(L-BFGS)로 결합해 단일 모달 대비 식별 성능 개선
- **Human-in-the-loop** — 오식별이 곧 복약 사고인 도메인이라, 자동 확정 대신 Top-3 확인 단계를 설계에 못박음
- **2.6M 라벨 파싱 → MySQL 적재**, DUR 병용금기 검색 백엔드 구축
- Gradio 웹 데모 배포, `v1.0` 릴리스

> `YOLOv11` `ConvNeXt` `PaddleOCR` `PyTorch` `MySQL` `Solar LLM` `Gradio`

### 🧬 항원 MSA 편향 진단 및 활용 — 항체·항원 도킹

`SNU BK21 학부연구` · 이창한 교수 항체·면역학 연구실

AlphaFold3 계열 co-folder가 항체–항원 도킹에서 **공개 구조에 흔한(면역우세) 에피토프로 예측을 끌어당기는** 학습 편향이 존재한다는 가설을 세웠습니다. 그 편향이 항원 MSA를 통해 전달되는지 진단하고, MSA 깊이 반응(depth-response)을 pose 선택 신호로 쓰는 연구입니다.

- **leakage-free 설계** — 
- **핵심 발견**: 깊이가 아니라 **MSA 구성(composition)** 이 결합자리 선택을 좌우 (조성 8종 × 4런, 이질성 검정 `p=0.0025`)
- **budget-matched control** 로 best-of-N 설명 배제 (Fisher `p=3.9×10⁻⁸`)
- **End-to-End Pipeline 생성 **: MSA 구성 변화에 의해 제시된 후보 결합 자리를 기반으로 도킹하는 파이프라인을 구성했습니다. AlphaFold3로 해결하지 못하는 일부 복합체에 대해 더 높은 DockQ 값을 달성했습니다.

> `AlphaFold3` `Boltz-2` `Protenix` `HADDOCK` `순열검정` `Neff 정규화`

### 🎵 F-Sync — 의도-반응 괴리도(Gap) 분석

`FNC 미래 일경험 8팀` · **[Feellived/fsync-ai-agent](https://github.com/Feellived/fsync-ai-agent)**

소셜 리스닝이 “반응이 어땠는가”만 재는 데 그친다면, F-Sync는 **“기획이 의도한 메시지가 실제로 전달됐는가”** 를 라벨 단위로 수치화합니다.

- 밴드 8팀 유튜브 댓글 **107,505건** 으로 기준선을 세우고, 대상 곡 댓글 4,000건의 라벨 분포를 상대강도(lift)로 비교
- 기획안이 의도한 메시지 3개 중 **1개만 전달** 됐음을 정량 규명 — 가장 힘준 ‘밴드·정체성’은 `×0.99` 로 누수
- 의도하지 않은 ‘연주·악기’가 `×1.75` 로 최대 반응 → 기획 피드백 루프로 환원

> `NLP` `제로샷 분류` `임베딩` `Python` `pandas`

### 📈 통계적 추론과 회귀분석 — 투빅스 26기 정규세션

`강의자` · **[Feellived/tobigs-26th-stat-inference-regression](https://github.com/Feellived/tobigs-26th-stat-inference-regression)**

Framingham 심장연구 데이터 하나로 **EDA → 추론 → 회귀 → 예측** 을 관통하는 86슬라이드 강의와 Colab 과제를 제작했습니다.

- 학생별 시드(`MY_SEED`)를 달리해 **정답 복붙이 불가능한 과제** 를 설계 — 실행값에 근거한 해석이 변별점
- 리뷰 논문 *To Explain or to Predict?* (Shmueli, 2010)로 설명과 예측의 목표 차이를 강의 서사에 결합

> `statsmodels` `scikit-learn` `Jupyter` `통계 교육`

---

## 📫 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Feellived)
[![Notion](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/Juhyeong-Yoo-3acac1a3a28a81e5b023dc2ac2d0fb5a)

관심 있는 주제로 이야기 나누고 싶다면 언제든 Issue나 Discussion으로 남겨주세요.

</div>
