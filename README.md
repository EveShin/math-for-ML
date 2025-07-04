# 머신러닝을 위한 수학 학습 저장소

머신러닝과 딥러닝의 수학적 기초를 체계적으로 학습하고 실무 적용 능력을 기르기 위한 저장소입니다.

## 학습 목표

- 선형대수: 벡터, 행렬 연산 및 고유값 분해 이해
- 확률통계: 확률분포와 베이즈 추론 습득
- 미적분학: 최적화와 경사하강법의 수학적 기초
- 머신러닝 적용: 이론과 실제 알고리즘의 연결

## 저장소 구조

```
ml-math-study/
├── notebooks/                  # 학습 노트북
│   ├── 01_linear_algebra/
│   │   ├── vectors_matrices.ipynb
│   │   ├── eigenvalues_eigenvectors.ipynb
│   │   ├── svd_and_pca.ipynb
│   │   └── ml_applications.ipynb
│   ├── 02_probability_statistics/
│   │   ├── probability_basics.ipynb
│   │   ├── distributions.ipynb
│   │   ├── bayesian_inference.ipynb
│   │   └── ml_applications.ipynb
│   ├── 03_calculus_optimization/
│   │   ├── derivatives_gradients.ipynb
│   │   ├── optimization_methods.ipynb
│   │   ├── neural_network_math.ipynb
│   │   └── ml_applications.ipynb
│   └── 04_integration/
│       ├── complete_projects.ipynb
│       └── ml_implementations.ipynb
├── projects/                   # 완성된 프로젝트
│   ├── pca_implementation/
│   ├── bayesian_classifier/
│   ├── optimization_comparison/
│   └── neural_network_math/
├── exercises/                  # 연습문제
│   ├── linear_algebra_problems.ipynb
│   ├── probability_problems.ipynb
│   └── calculus_problems.ipynb
├── utils/                      # 유틸리티 모듈
│   ├── linear_algebra_utils.py
│   ├── probability_utils.py
│   ├── optimization_utils.py
│   └── visualization.py
└── references/                # 참고자료
    ├── formula_sheets.md
    └── resources.md
```

## 학습 계획

### 1단계: 선형대수 (1-4주)
**핵심 개념**
- 벡터와 벡터 공간
- 행렬 연산과 역행렬
- 내적과 노름
- 선형 변환

**핵심 실습**
- 벡터 연산 구현
- 행렬 곱셈 최적화
- 선형 변환 시각화

### 2단계: 고유값과 특이값 분해 (5-7주)
**핵심 개념**
- 고유값과 고유벡터
- 특이값 분해 (SVD)
- 주성분 분석 (PCA)
- 차원 축소 이론

**핵심 실습**
- 고유값 분해 구현
- PCA 알고리즘 구현
- 이미지 압축 응용

### 3단계: 확률 기초 (8-10주)
**핵심 개념**
- 확률 정의와 조건부 확률
- 베이즈 정리
- 확률분포 (정규분포, 베르누이, 포아송)
- 기댓값과 분산

**핵심 실습**
- 확률분포 시뮬레이션
- 베이즈 정리 적용
- 몬테카를로 방법

### 4단계: 통계 추론 (11-13주)
**핵심 개념**
- 최대우도추정 (MLE)
- 베이즈 추정
- 가설검정과 신뢰구간
- 중심극한정리

**핵심 실습**
- MLE 구현
- 베이즈 분류기 구현
- 가설검정 시뮬레이션

### 5단계: 미분과 최적화 (14-16주)
**핵심 개념**
- 편미분과 전미분
- 그래디언트와 방향도함수
- 연쇄법칙
- 경사하강법

**핵심 실습**
- 다변수 함수 미분
- 경사하강법 구현
- 뉴턴 방법 비교

### 6단계: 머신러닝 통합 응용 (17-20주)
**핵심 개념**
- 신경망 역전파의 수학
- 정규화 기법의 확률적 해석
- 손실함수와 최적화의 연결
- 일반화 이론

**핵심 실습**
- 신경망 수학적 구현
- 정규화 효과 분석
- 최적화 방법 비교

## 주요 프로젝트

### 프로젝트 1: PCA 완전 구현
**목표**: NumPy만을 사용한 주성분 분석 알고리즘 구현
**기술**: 공분산 행렬, 고유값 분해, 차원 축소 이론

### 프로젝트 2: 베이즈 분류기
**목표**: 베이즈 정리를 직접 적용한 나이브 베이즈 분류기
**기술**: 베이즈 정리, 확률분포, 최대사후확률 추정

### 프로젝트 3: 경사하강법 비교 분석
**목표**: 다양한 1차 최적화 알고리즘 구현 및 성능 분석
**기술**: 볼록 최적화, 수렴 분석, 모멘텀 방법

### 프로젝트 4: 신경망 수학적 구현
**목표**: 역전파 알고리즘의 수학적 원리를 직접 구현
**기술**: 연쇄법칙, 자동 미분, 그래디언트 계산

## 핵심 기술 역량

### 수학적 이해
- 추상적 개념의 기하학적 직관
- 수학적 증명과 유도 능력
- 이론과 실제의 연결 능력
- 수치적 안정성 고려

### 구현 능력
- 수학 알고리즘의 효율적 구현
- 시각화를 통한 개념 설명
- 성능 분석 및 최적화
- 다양한 예제를 통한 검증

### 응용 역량
- 머신러닝 문제의 수학적 모델링
- 알고리즘의 수학적 직관 설명
- 성능 분석의 이론적 근거
- 새로운 방법론의 수학적 해석

## 학습 자료

### 핵심 교재
- "Linear Algebra and Its Applications" - Gilbert Strang
- "확률과 통계" - 이상열
- "Calculus" - James Stewart
- "The Elements of Statistical Learning" - Hastie, Tibshirani, Friedman

### 온라인 강의
- MIT 18.06 Linear Algebra
- Khan Academy 확률통계
- 3Blue1Brown Essence of Calculus
- Coursera Mathematics for Machine Learning

### 수학 도구
- GeoGebra (기하학적 시각화)
- Wolfram Alpha (수식 계산)
- Desmos (함수 그래프)
- Symbolab (단계별 풀이)

### 실습 자료
- NumPy 수치해석 예제
- SciPy 최적화 튜토리얼
- Matplotlib 수학 시각화
- SymPy 기호 수학

## 개발 환경

```bash
# 기본 수학 라이브러리
pip install numpy scipy matplotlib seaborn
pip install jupyter pandas scikit-learn
pip install sympy  # 기호 수학

# 시각화 도구
pip install plotly ipywidgets
pip install manim  # 수학 애니메이션 (선택)

# 성능 측정
pip install memory-profiler line-profiler
```

## 진도 관리

### 주간 목표
- 1-4주: 선형대수 기초 완료
- 5-7주: 고유값/SVD 마스터
- 8-10주: 확률 기초 완료
- 11-13주: 통계 추론 완료
- 14-16주: 미분과 최적화 완료
- 17-20주: ML 통합 응용 완료

### 체크포인트
- 각 개념의 ML 적용 사례 이해
- 관련 알고리즘 직접 구현
- 시각화를 통한 직관적 이해
- 실제 데이터셋 적용 실습

### 완료 기준
- 구현한 알고리즘: ___개
- 완료한 프로젝트: ___개
- 이해한 ML 연결고리: ___개
- 시각화한 수학 개념: ___개

## 학습 방법

### 효과적 접근법
- 개념 이해 → 수식 유도 → 코드 구현 → 시각화
- 손으로 계산 후 Python으로 검증
- 실제 ML 문제와 연결하여 학습
- 다양한 예제로 일반화

### 수학적 사고법
- 정의에서 시작하여 정리로 확장
- 기하학적 직관과 대수적 계산의 균형
- 예외 사례와 경계 조건 고려
- 일반화 가능성과 한계 분석

---