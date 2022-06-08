# PJ_modeling_7
yeardream 2nd, offline group 7, Mini Project - Modeling

##Topic & Data : PUBG Finish Placement Prediction
Data from : https://www.kaggle.com/competitions/pubg-finish-placement-prediction/data
- sample_submission.csv
- test_V2.csv
- train_V2.csv

**[PUBG Finish Placement Prediction](https://www.kaggle.com/competitions/pubg-finish-placement-prediction/overview)**
- 사용자가 **몇 등으로 게임을 종료할지(final stats)를 예측**하는 과제입니다.

Who? : 문석민, 오세연, 윤상현, 진승범, 최윤아


### Daily Records
**07Jun_01.ipynb**
- 6/7 To do
   * Obj columns만 날리고, 러프하게 돌려보기
   * obj + drop 한 col 날리고, 러프하게 돌려보기

~ 6/9 오후 회의(15:00) 전까지 To do list
* main
   - 전처리
   - EDA
* sub
   - 이상치 여부 확인
   - 타겟 값과의 상관관계 분석
   - 필요하다면 전처리
   - 칼럼 담당할 때 합당한 이유가 필요.
   - 전처리는 주석화한 코드
   - 칼럼이 겹칠 경우, 두 가지 방법 중 하나를 채택
      1) 각자 전처리를 한 뒤, 회의에서 비교 후 하나를 채택
      2) 칼럼이 겹치는 사람들끼리 합의 후 전처리 진행 _ 코드 작성자가 본인의 깃헙에 올린다.


오세연의 담당 columns : 
=> 우승과 회복, 어시스트, 부스트가 상관관계가 있을 것 같아서 확인.
   - matchType
   - damageDealt
   - boosts
   - heals
   - assists
   - revives
