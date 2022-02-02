# Perceptron 구현
perceptron이란? 두뇌의 인지 능력을 모방하도록 만든 인위적인 네트워크를 의미한다.









<img width="600" alt="neuron-node1" src="https://user-images.githubusercontent.com/98728682/152082670-7570fc1b-2ebe-4cc9-bfbd-6922abd53609.png">

뇌의 뉴런이 이전 뉴런들로부터 신호를 받고 처리한 다음 뉴런에게 신호를 전달하듯이, 

perceptron도 이전 데이터로부터 중요한 정보를 받고, 받은 정보를 처리한 뒤, 다음 perceptron에 정보를 내보낼지 결정한다. 

# Activation function의 역할
1.가중합(<img src="https://latex.codecogs.com/gif.latex?$\Sigma w_i x_i" />)이 임계값 이하이면 0(에 가까운 값)으로, 이상이면 1(에 가까운 값으)로 내보내주는 구조

2.다음 perceptron에 보낼 신호의 강도를 결정

3.Step func, Sigmoid func, ReLu가 대표적으로 쓰임

\Sigma
