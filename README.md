# syntactic_complexity_kcbert_model

## 개요
- 서혁 외(2013)의 문장 복잡도 분석 체계에 따라 '국립국어원 구문 분석 말뭉치(버전 2.0)'의 문어 말뭉치 150,082문장의 통사적 복잡도 점수를 계산.
- 이후 해당 데이터셋을 사용하여 KcBERT 모델(https://github.com/Beomi/KcBERT)을 파인튜닝함으로써 통사적 복잡도 측정 모델을 구현.
- 접근 링크: https://1drv.ms/f/c/4dded1a4d967e222/IgAJjCJrA-xGTLrtaW7FfBOyASzxSOwcI7X24-qm9eTmlOA?e=dkknRw

## 모델별 설명
- model_basic.pt: 기본 문형 점수 측정 모델
- model_plus1.pt: 첨가 조건 1 점수 측정 모델
- model_plus2.pt: 첨가 조건 2 점수 측정 모델
- model_sum.pt: 통사적 복잡도 합산 점수 측정 모델

## 참고문헌
- 나상수, 김범진(2023), Implementation of Deep Learning Model-based Korean Sentence Syntactic Complexity Assessment Model, 응용언어학 39(3), 103-129쪽.
