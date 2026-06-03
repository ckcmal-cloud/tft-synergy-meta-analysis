# TFT 시너지 메타 분석
> Riot Games TFT Season 3 Match Data 기반 메타 구조 분석 및 밸런스 개선 인사이트 도출


## 프로젝트 목표:
> 소수 시너지에 플레이가 집중되어 게임 다양성 하락 문제에 대한 플레이 다양성 유도를 위한 보상 시스템 설계


## Dataset
- 원본 데이터: 399,998건 
- 전처리 후 데이터: 328,532건 
- 유효 매치 수: 49,878개 
- 활성 시너지: 23개


## Analysis

### 1. 메타 구조 분석

- Synergy Pick Rate 분석
- Top4 Rate 분석
- Pareto Chart 기반 선택 집중도 분석
- Gini Coefficient
- HHI(Herfindahl-Hirschman Index)

### 2. 조합 패턴 분석

- 시너지 조합 상관관계 분석
- 주요 조합 패턴 식별
- 순위별 레벨 분포 분석

### 3. 밸런스 개선 아이디어 도출

- 고인기·저성능 시너지 식별
- 저인기·고성능 시너지 발굴
- 보상 가중치 기반 메타 다양성 시뮬레이션


## 주요 결과

- 상위 5개 시너지가 전체 선택의 약 45% 차지
- 인기 시너지와 실제 성과가 항상 일치하지 않음
- 메카 파일럿–잠입자, 반군–우주선 등 강한 조합 패턴 확인
- 상위권 플레이어 대부분이 8~9레벨 구간에서 게임 종료
- 저인기·고성능 시너지 다수 발견
- 보상 정책 시뮬레이션 결과 메타 집중도(HHI) 2.31% 감소


## 인사이트

- 롱테일 메타 활성화
- 덱 가치 재평가
- 신규 콘텐츠 수명 연장


## 분석 기법

- Pick Rate·Top4 Rate 분석
- Pareto 분석
- Gini·HHI 집중도 분석
- 카이제곱 검정
- ANOVA
- Kruskal-Wallis 검정
- 시너지 조합 상관관계 분석


## 데이터 출처

- [Kaggle TFT Match Data](https://www.kaggle.com/datasets/gyejr95/tft-match-data)
