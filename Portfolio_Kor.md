# 📜 Doyeon Park Portfolio
Doyeon Park - yeon-do Portfolio for Technical assessment



# 📌 Projects Overview
| 프로젝트 | 기간 | 역할 | 기술 스택 |
|---|---|---|---|
| 한양대학교 데이터마이닝 연구실 학부연구생 | 2025.07 ~ 현재 | 학부연구생 | Python, PyTorch, Generative Recommendation |
| 응용회귀분석 | 2025.09 ~ 2025.12 | Data Analyst | R, Statistics |
| Fashion Style Image Classification & Preference Prediction | 2024.09 ~ 2024.11 | Model Architect | Python, PyTorch |
| Re:Fact (Web Game) | 2025.03 ~ 2025.07 | Frontend Developer | JavaScript, Phaser3 |


# 📝 Projects

## 1. Generative Recommendation & Semantic Graph Research 🔬

**한양대학교 데이터마이닝 연구실 학부연구생**

Generative Recommendation 분야의 선행 연구를 분석하고, 기존 모델의 재현과 평가 환경 구축을 수행하고 있습니다. 초기에는 Sequential Recommendation 관련 논문을 조사·발표하고 GRAM을 비롯한 baseline 모델을 재현했으며, 이후 baseline 간 평가 방식의 차이를 분석하고 평가 방법을 통일했습니다. 현재는 다양한 case에 대한 반복 실험을 통해 모델의 성능과 특성을 분석하고 있습니다.

- **기간:** 2025.07 ~ 현재
- **역할:** Literature Review, Baseline Reproduction, Experimental Analysis
- **기술:** Python, PyTorch, VSCode

### 주요 기여

- **논문 분석 및 발표:** Sequential Recommendation 및 Generative Recommendation 관련 선행 연구를 조사하고 주요 방법론과 연구 방향을 발표했습니다.
- **Baseline 재현:** GRAM을 비롯한 기존 모델을 직접 재현하여 후속 실험을 위한 baseline을 구축했습니다.
- **평가 방법 통일:** baseline별 evaluation setting의 차이를 분석하고, Candidate Sampling 방식에서 Full Ranking 방식으로 평가 환경을 통일했습니다.
- **Case별 실험 및 분석:** 다양한 조건에서 반복 실험을 수행하며 모델의 성능 변화와 특성을 비교·분석하고, 연구 방향에 필요한 실험 결과를 축적하고 있습니다.
- **Graph 기반 분석:** 연구 과정에서 데이터의 구조적 관계를 활용하기 위한 Graph를 구성하고 Shortest Path 분석 코드를 구현했습니다.
  <img src="https://github.com/user-attachments/assets/85944ba8-7d97-4b25-8f26-f0074322d8fc" width="70%"/>

**🎞 연구 관련 코드**
*연구의 주요 architecture는 현재 개발 및 연구가 진행 중이므로, 공개 가능한 범위에서 데이터 처리 및 Graph 분석 코드를 정리했습니다.*
* [👉 View KG Construction & Shortest Path Analysis Codes](https://github.com/yeon-do/llmbased-rec/blob/main/FIXED_2_analyze_shortest_paths.py)
<br>

## 2. 통계적 모델링 및 회귀분석 📊

**한양대학교 수학과 「응용회귀분석」**

데이터의 특성과 분석 목적에 따라 단순·다중 선형회귀부터 Ridge, Lasso 등의 정규화 회귀까지 다양한 통계적 모델을 적용했습니다. 모델의 가정을 검토하고 결과를 비교·논의하며 분석 과정의 타당성을 점검했습니다.

- **기간:** 2025.09 ~ 2025.12
- **역할:** Data Analyst & Final Presenter
- **기술:** RStudio
- **언어:** R

### 주요 기여

- **단계별 회귀 모델링:** 단순 선형회귀와 다중 선형회귀부터 Ridge와 Lasso까지 데이터의 특성에 맞는 회귀 방법을 적용하고, 각 분석에 필요한 코드를 직접 작성했습니다.
- **모델 진단 및 결과 검토:** 잔차 분석을 통해 정규성 및 등분산성 등의 회귀 가정을 검토하고, 다른 팀과 결과를 비교·논의하며 모델의 한계와 개선 방향을 확인했습니다.

**🎞 최종 프로젝트: 더미변수 회귀분석 심화 분석**

최종 프로젝트에서는 병아리 성장 데이터와 칠면조 체중 데이터를 활용해 비타민 종류와 연령대 등 범주형 변수가 정량적 결과에 미치는 영향을 분석했습니다.

Partial F-test를 활용해 회귀직선의 평행성 및 일치 여부를 단계적으로 검정하고, 분석 결과를 바탕으로 적절한 모델을 선택하는 과정을 정리했습니다. 또한 표본 수가 적을 때 발생할 수 있는 통계적 한계를 함께 분석했습니다.

<img src="https://github.com/user-attachments/assets/18423891-28a9-48c3-ace4-1a45c6e4ecc5" width="70%">

[👉 실습 코드, 최종 발표자료 및 보고서](https://github.com/yeon-do/anlaysis-application-regression.git)

<br>

## 3. Fashion Style Image Classification & Preference Prediction 👟

**과학기술정보통신부·한국지능정보사회진흥원(NIA) Data Creator Camp**

패션 이미지의 스타일을 분류하는 Deep Learning 모델을 개발하고, 분류 모델에서 추출한 Feature Vector의 유사도를 활용해 사용자의 선호를 예측하는 추천 알고리즘을 구현했습니다.

- **기간:** 2024.09 ~ 2024.11
- **역할:** Model Architect & Data Preprocessing Lead
- **기술:** VSCode, Colab, PyTorch, U-2-Net, Mask R-CNN, ResNet-18
- **언어:** Python

### 주요 기여

- **이미지 전처리 Pipeline 구축:** U-2-Net과 Mask R-CNN을 활용해 이미지의 배경 제거와 객체 분할을 수행하는 전처리 과정을 구축했습니다. 또한 Data Augmentation을 적용해 모델의 일반화 성능을 높이고자 했습니다.
- **이미지 분류 모델 개발:** ResNet-18을 구현하고 학습시켜 여러 연도의 패션 이미지를 스타일별로 분류했습니다.
- **유사도 기반 선호 예측:** 분류 모델에서 Feature Vector를 추출하고 이미지 간 거리를 계산해 유사도를 구했습니다. 이를 Item Similarity로 활용하여 Item-based Collaborative Filtering 방식의 선호 예측 알고리즘을 구성했습니다.

### 🏆 수상

한국지능정보사회진흥원(NIA) Data Creator Camp에서 **우수상(2위)**을 수상했습니다. Computer Vision과 Recommendation을 결합한 접근 방식과 모델 구성의 논리성을 바탕으로 프로젝트의 완성도를 인정받았습니다.

**🎞 프로젝트 발표자료 및 코드**
* [👉 View Project Presentation (PPT) & Source Code](https://github.com/yeon-do/Data_create_camp.git)
* [💻 View Simplified Core Code (Classification, Feature Extraction & Similarity RecSys)](https://github.com/yeon-do/Data_create_camp/blob/main/Simplified%20Core%20code(Classification%2C%20Feature%20Extraction%20%26%20Similarity%20RecSys).py)
<br>


## 4. Web 기반 재활용 교육 게임 'Re:Fact' ♻️

**친환경 패키징 기업 Refeely 협업 프로젝트 (KAKAO Tech Impact & 한양대학교)**

종이팩의 낮은 재활용률 문제를 개선하기 위해 올바른 분리배출 방법을 게임을 통해 학습할 수 있도록 설계한 교육용 Web Game을 개발했습니다.

- **기간:** 2025.03 ~ 2025.07
- **역할:** Frontend Developer
- **기술:** VSCode, Phaser3
- **언어:** JavaScript

### 주요 기여

- **Frontend 및 Game Engine 개발:** Phaser3와 JavaScript를 활용해 폐기물 분류 게임, 전처리 행동 미션, 퀴즈 등 핵심 게임 로직을 구현하고 사용자 경험을 고려한 UI/UX를 개발했습니다.
- **프로젝트 기획 및 요구사항 반영:** Refeely CEO와 직접 소통하며 사업 요구사항을 기술적 기능으로 구체화했습니다. 제품 QR 코드와 연계하고 게임 포인트를 기업 온라인몰에서 사용할 수 있도록 실제 보상 시스템을 구현했습니다.
- **ESG 문제 해결:** 올바른 분리배출 행동을 유도하는 교육용 솔루션을 개발했으며, 테스트 사용자 중 **77.6%가 친환경 행동 의향이 높아졌다고 응답**하는 결과를 확인했습니다.

<img src="https://github.com/user-attachments/assets/b37bbedc-85ec-44b7-8b95-4043c8bac0c6" width="60%">

<br>**🔗 프로젝트 링크:**
* [🎮 Play the Game on Web](https://funny-pasca-8573bf.netlify.app/)
* [👉 View Detailed & Source Code](https://github.com/yeon-do/TFI_CAMPUS_HANYANG_25Spring_REPACT.git)
