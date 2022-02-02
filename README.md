# Perceptron 구현
perceptron이란? 두뇌의 인지 능력을 모방하도록 만든 인위적인 네트워크를 의미한다.









<img width="600" alt="neuron-node1" src="https://user-images.githubusercontent.com/98728682/152082670-7570fc1b-2ebe-4cc9-bfbd-6922abd53609.png">

뇌의 뉴런이 이전 뉴런들로부터 신호를 받고 처리한 다음 뉴런에게 신호를 전달하듯이, 

perceptron도 이전 데이터로부터 중요한 정보를 받고, 받은 정보를 처리한 뒤, 다음 perceptron에 정보를 내보낼지 결정한다. 



# Activation function의 역할과 종류
1.가중합이 임계값 이하이면 0(에 가까운 값)으로, 이상이면 1(에 가까운 값으)로 내보내주는 구조

2. 다음 perceptron에 보낼 신호의 강도를 결정

3. Step func, Sigmoid func, ReLu가 대표적으로 쓰임


(1) step function

![images](https://user-images.githubusercontent.com/98728682/152089932-889279c8-cb4f-408a-840c-5c06f3708279.png)

● 미분 값이 0이고, threshold 기준으로 극단적으로 0, 1로 나뉜다.

(2) sigmoid function

<img src="https://user-images.githubusercontent.com/98728682/152089956-9cdfe83d-9f92-4251-84b5-ad2fd355a743.png"  width="320" height="250">

● 입력의 절대값이 포화하면 일정값을 가짐

● 그 사이의 값에 대해서는 출력이 서서히 매끄럽게 변함

(3)ReLU

<img src="https://user-images.githubusercontent.com/98728682/152089992-12fb843d-f62a-49a7-9871-1632dc5073cb.png"  width="320" height="250">

● 0기준으로 output이 선형적으로 증가

● 단순하고 계산량 적음

● 학습이 빠르고 최종 결과도 더 좋은 경우가 많음
