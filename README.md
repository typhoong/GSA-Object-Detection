담당자: 김태훈 (thkim@mnc.ai)

# 2021 글로벌 창업 사관학교 in-class 과제

[이미지] 도로 위 객체 인식 모델  
[인클래스 링크](https://www.kaggle.com/competitions/road-od)

## 문제 설명
도로주행 이미지에서 17종의 객체 영역을 검출하고 분류하는 Object Detection 과제

## 베이스라인
YOLOv5

## 평가지표
MAE
- Object Detection 모델의 성능 평가 방법 중 하나인 mAP@IoU=0.75 등을 사용하려 하였으나, Kaggle in class 플랫폼의 한계로 각 이미지의 클래스 개수에 대한 MAE를 리더보드 지표로 사용