# 근전도 센서를 활용한 의사전달 어플리케이션:dizzy:

### Flow Chart
![c1](https://user-images.githubusercontent.com/58021968/107882341-0cdd3580-6f2c-11eb-839e-6d80f3b12779.PNG)
- 근전도 센서(SEN0240)를 통해 아두이노 보드에서 받은 신호로 Dataset을 구축
<br>

<br>

![image](https://user-images.githubusercontent.com/58021968/107882394-65143780-6f2c-11eb-9eb7-90d80094a605.png)
- 신경망 훈련과정을 진행

<br>

## 근전도 센서를 통해 수집한 데이터
![image](https://user-images.githubusercontent.com/58021968/107849178-e2f91580-6e3c-11eb-9ff5-54fbabb1320f.png)

## 나열해둔 데이터들 
![image](https://user-images.githubusercontent.com/58021968/107849187-f1dfc800-6e3c-11eb-8dab-bff433435986.png)

## 학습진행
![image](https://user-images.githubusercontent.com/58021968/107849206-1e93df80-6e3d-11eb-95ea-6005c260dde2.png)

## Model Summary
- layer 활성화 함수 -> relu, sigmoid
- 최적화 함수 -> adam
- 손실 함수 -> binary_crossentropy

![image](https://user-images.githubusercontent.com/58021968/107849201-1176f080-6e3d-11eb-8f82-9e76ed73915b.png)

## 학습률과 손실율 그래프
![image](https://user-images.githubusercontent.com/58021968/107849111-5baba200-6e3c-11eb-81ec-5b9f9acf8b71.png)
