# CheonAn-Old-man-driver-license (고령 운전자 면허 갱신 절차 강화 및 교통 정책 제안)
Won the bigger award in 2024 Cheonan city Data Analysis contest.

## 개요 :
고령 운전자의 사고 심각도 예측 모델을 활용하여 읍면동 별 사고 심각도를 예측하고, 도로 주행 구간을 선정한다. 면허 갱신 관련 정책을 제시하고, 개선안 도입 시 사고 절감 편익을 산출한다.

## 주요 기능 (사고 심각도 예측 모델)



## 실행 코드
- 'Buffer_add' : 읍면동 주요 지점 주위 200m 버퍼 내 존재하는 고령자 주요 이용시설 수 기록 (데이터 전처리)
- 'Transfer_coordinates2EPSG:5181' : ESPG:4326 -> ESPG:5181 위경도 좌표 변환 (데이터 전처리)
- 'CheonanModel_final.ipynb' : 지역별 사고심각도에 대해 XGBoost•LightGBM•CatBoost를 Optuna로 학습허고, 가중치 최적화로 앙상블해 최종 예측하는 코드

## 결과 HTML
- 'CheonanModel_final.html'

## 프로젝트 세부사항
https://www.notion.so/1bb79f19815e813eb18bf8ee1f143a0b?source=copy_link

> 본 저장소는 포트폴리오 열람용입니다. 원 데이터는 용량/라이선스 사유로 비공개이며,
> 결과 재현 대신 코드•출력(JUPYTER/HTML)을 제공합니다.
