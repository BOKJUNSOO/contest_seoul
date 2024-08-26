# Contest

Seoul linked open data Contest
서울시 교육청에서 주관한 공모전 결과물 입니다.

데이터는 2020~2024년도 서울시교육청에서 수집한 데이터를 이용했습니다.

KEY 값을 년도-학교코드로 설정했기 때문에 학교명이 같아도 년도가 다르다면 다른 학교로 취급했습니다.

Target이 되는 변수는 학교별 점수입니다.


## Directory Structure

```
| data
  |- 2020~2024 SCHOOL DATASET (with preprocessing)
| job
  |- 0.dataAnalysis : EDA
  |- 1.combineData : combine dataset
  |- 2.modelingAndval : modeling(Regressor)
  |- 3.EDA : result
```

