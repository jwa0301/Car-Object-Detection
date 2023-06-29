# DACON 합성데이터 기반 객체 탐지 AI 경연대회

train data는 합성데이터로, test data는 실제 데이터로 이루어져있음.

총 34가지의 자동차 세부모델에 대해 판별.

## 학습
- yolov8 모델 중 제일 층이 많고 성능이 좋은 yolov8x 선택
- yolov8x 모델의 세부 hyper parameter를 바꾸며 최고 성능을 보이는 hyper parameter 조합 선택
