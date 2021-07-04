# 2021-1 현대자동차 데이터분석 해커톤

<br>

2021년 현대자동차에서 주관한 재구매 고객 맞춤형 마케팅을 위한 데이터분석 해커톤 코딩 소스와 결과서에 대한 자료입니다. (데이터는 삭제)



<br>



---

## Task 1

<문제 정의>

- 주어진 가상 구매 고객 Data를 바탕으로 재구매고객 유형에 대한 분리/추정 로직 개발
- "대차" 및 "추가구매" 구분 결과에 대해 EDA를 수행해 인사이트 도출.

<br>

<embed src="./TASK1.pdf" type="application/pdf">









<br>

---

## Task 2

- 







---------------

## 데이터 수집 



[KBO 공식 홈페이지](https://www.koreabaseball.com/Schedule/Schedule.aspx) 에서 2020 시즌 KBO 전체 경기에 대한 정보를 크롤링.

- 경기일자
- 홈팀 / 원정팀
- 홈팀 스코어 / 원정팀 스코어

- 홈팀 선발투수 / 원정팀 선발투수



![Image](./Image/data.png)



<br>

---------------

## 모델링



- 프로야구 10개 팀 각각의 공격력/수비력 모수 추정



![Image](./Image/model.png)





![Image](./Image/modelling1_result.png)



<br>

---

# 결과 

![Image](./Image/final.png)

<br>

**<경기결과 시뮬레이션>**

![Image](./Image/prediction.png)






---------------

## 발전 방향

- 베이지안 모델의 유용성/확장성을 적극 이용
- 창의적으로 새로운 변수를 추가해서 모델을 정교화

