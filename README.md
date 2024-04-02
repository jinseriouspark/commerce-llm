# commerce-llm
24.03.18 ~

배경 : 상품의 '필터조건' 으로 활용할 수 있는 기준이 필요

목적 
1. 리뷰에서 상품에 도움이 되는 키워드를 찾아, 상품의 '필터조건' 으로 활용 시도 -> 상품 리뷰 파인튜닝

진행 방법 
<키워드 추출>
  1. 키워드 추출 extract keywords : 배송 관련된 키워드 추출
  2. llm을 활용한 키워드 평가 evaluation with prompt-engineering ( 진행중)
    - openAI
    - keybert & Mistral 7b
  4. 평가된 키워드 기반으로 재학습 re-training

<상품 필터 조건 활용>
  1. 최종 추출된 키워드로 분류 모델 생성
