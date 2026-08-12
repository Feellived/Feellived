<div align="center">

## 안녕하세요! 👋<br><br>저는 생명과학의 해결되지 않은 질문들을 통계와 머신러닝, 실험으로 풀어내는 연구자, 유주형입니다.

</div>

---

## 👨🏻‍🔬 Experiences

- 🧬 **서울대 항체·면역학 연구실** — AlphaFold3 계열 구조 예측 모델이 항체–항원 결합 자리를 어떻게 정하는지 통제 실험으로 규명하고, 정답 구조를 참조하지 않는 결합 자리 예측·재도킹 파이프라인을 구축했습니다.
- 🧫 **고려대 RNA 대사 및 세포 신호 전달 연구실** — mTORC1 중심의 암세포 신호 전달, 종양 미세 환경 연구 과정에서 단백질, 전사체 정량 실험을 진행했습니다.
- 💊 **데이터 분석/AI 학회 투빅스(ToBig's) 25기** — 25기 운영 부장으로 동아리를 이끌었습니다. <br>1) Computer vision, OCR, LLM을 이용한 복약지도 서비스 **PILLAR** <br>2) ADMET 예측 모델의 입력 서열 특성에 따른 불안정성 정량 플랫폼 **SENSE** (진행중)
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

### 🧬 MSA 조성 편향 규명과 결합 자리 유도 도킹 — 항체·항원 구조 예측

`SNU BK21 학부연구` · 이창한 교수 항체·면역학 연구실 · **[Feellived/msa-composition-bias](https://github.com/Feellived/msa-composition-bias)** · **[Feellived/epitope-guided-docking](https://github.com/Feellived/epitope-guided-docking)**

AlphaFold3 계열 co-folder는 단백질 구조는 잘 접지만 항체–항원 **결합 자리**에서는 자주 틀리고, 모델이 내놓는 전역 신뢰도(ipTM)는 계면의 옳고 그름을 가르지 못합니다. 그 원인을 항원 MSA에서 찾고, 거기서 얻은 성질을 결합 자리 예측에 이용했습니다.

**① 현상 규명 — MSA 조성이 결합 자리 선택을 좌우한다**

MSA의 **깊이(서열 수)를 고정한 채 구성원만 다시 뽑는** 설계로, 깊이 감소·best-of-N이라는 두 대안 설명을 배제했습니다. 학습 컷오프 이후 공개된 복합체 30종 × 960회 실행.

- 같은 조성을 반복하면 같은 자리가 재현되고 조성을 바꾸면 다른 자리로 이동 — 자카드 **조성 내 0.503 대 조성 간 0.413**, 30종 전원 성립 (부호검정 `p = 1.9×10⁻⁹`)
- 복합체별 순열검정 **26/30종 유의** (우연 기댓값 1.5종, 이항검정 `p = 3.4×10⁻³⁰`)
- 같은 실행 예산에서 조성 재추첨이 시드 반복보다 더 많은 자리를 찾음 — **24/30종**, 중앙값 +0.47 (`p = 1.8×10⁻⁴`)
- 다만 **변화의 방향은 일정하지 않아** 조성 재추첨은 개선 수단이 아니라 후보 생성 수단이며, 선택 단계가 필요하다는 결론으로 이어집니다

**② 파이프라인 — 정답 구조를 어느 단계에서도 보지 않는 4단계 구조**

```
① 생성   MSA 조성 재추첨으로 결합 자리 후보를 넓힌다        (Protenix)
② 조립   조성 간 투표로 후보 자리를 세운다
③ 선택   정답 없이 후보 하나를 고른다                      (AbEpiScore-1.0)
④ 재도킹 고른 자리를 제약으로 주고 다시 접는다              (Boltz-2)
   게이트  무제약 예측의 신뢰도 < 0.75 이면서 후보 ≤ 3개일 때만 개입
```

- 생성 **23/30종** → 선택 **17/30종** → 적용 **5/16종**에서 DockQ 개선
- 8q7s_H는 DockQ **0.014 → 0.327**, 결합 자리 겹침 0.150 → 0.867 (나머지 세 대조 조건은 0.015 이하)
- **개입 대상 선별이 결정적** — 게이트를 통과한 16종은 평균 +0.052이나, 30종 전체에 개입하면 평균 −0.049
- **AlphaFold 3 대비** 자리 축에서 우위 — AlphaFold 3가 5개 결과 모두 결합 자리를 전혀 회복하지 못한 복합체(겹침 0.000)에서 0.824를 달성

> `Protenix` `Boltz-2` `Chai-1` `AlphaFold3` `HADDOCK` `DockQ` `순열검정` `Fisher 결합` `Neff 정규화`

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
