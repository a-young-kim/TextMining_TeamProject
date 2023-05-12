# TextMining_TeamProject
아마존 패션 데이터를 이용한 리뷰 생성기   
출처 : https://jmcauley.ucsd.edu/data/amazon/


## 데이터 전처리

## 데이터 EDA

## 데이터 추출

## 문장 분리 
 - 문장 단위로 분리된 아마존 패션 데이터를 배송, 사이즈, 색상, 퀄리티로 구분한다. 
 - text_to_sentence_num.csv는 각각 8만개 정도의 data를 가지고 있지만 '!', '?'와 같은 특수 문자로만 구성된 값들이 존재하여 이를 제거해야 한다.  

      | 구분 | Label |
      | ------------ | ------------- |
      | 배송 | 0  |
      | 사이즈 | 1  |
      | 색상 | 2 |
      | 퀄리티 | 3 |


## 키워드에 따른 문장 분류기

## 긍부정 분류기

## 리뷰 생성 모델
