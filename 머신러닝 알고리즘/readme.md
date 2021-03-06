머신러닝 알고리즘은 크게 3가지로 나눌 수 있다.         

Supervised Learning   /   Unsupervised Learning   /   Reinforcement Learning          

​              

Supervised Learning (지도 학습)
-----------------------------------------

이름에서부터 느껴지듯이 이 알고리즘은 데이터에 대한 label, 즉 이 데이터가 무슨 데이터인지에 대한 정답을 알려준 상태에서 기계를 학습시키는 방법이다.       

때문에 학습 데이터는 (data, label) 형태로 만들어지게 되고 학습이 잘 되었는지 테스트할 때에는 data만 주고 알고리즘이 그에 맞는 label을 맞게 출력하는지 확인하면 된다.         

이 지도 학습으로 풀 수 있는 문제는 크게 Classification (분류) 와 Regression (회귀) 가 있다.       

Classification은 데이터를 어떤 값으로 특정할 수 있는 문제이고 (이 동물은? 개)         

Regression은 데이터를 바탕으로 값을 예측하는 문제이다. (이 동네 커피값은 어느 정도? 3000원)           

지도 학습에서 주로 사용되는 구조는 CNN과 RNN이다.         

​                          


Unsupervised Learning (비지도 학습)
-------------------------------------------

이 알고리즘은 데이터에 대한 label을 주지 않은 채 데이터만 주고 기계보고 알아서 학습하라고 하는 방법이다.      

때문에 학습 데이터는 (data) 형태로 만들어지게 된다.        

이 비지도 학습으로 풀 수 있는 문제는 주로 Clustering (클러스터링) 이 있다.       

이 학습은 데이터의 숨겨진 특징 (hidden feature) 나 구조를 발견하는데 사용되는데       

예를 들어 대량의 뉴스 기사들을 입력으로 주었을 때 클러스터링 알고리즘을 사용해 각 기사에 숨겨진 특징을 잘 파악하면 뉴스 기사들이 각 카테고리별로 (정치, 경제, 스포츠 등등) 묶이는 것이다.         

비지도 학습에서 주로 사용되는 구조는 AutoEncoder 이다.        

​                  

## **Reinforcement Learning (강화 학습)**

이 알고리즘은 위의 두 알고리즘과는 살짝 다른 종류의 학습 알고리즘이다.        

위의 두 알고리즘이 학습할 데이터가 주어진 정적인 상태 (static environment) 에서 학습을 진행했다면        

강화 학습 알고리즘은 주어진 환경 (state) 에 대해 어떤 행동 (action) 을 취하고 이로부터 어떤 보상 (reward) 를 얻으면서 학습을 진행하는 방식이다.         

이 때 당연하겠지만 얻는 보상을 최대화하도록 학습이 진행된다.       

즉 강화 학습은 학습할 데이터를 실시간으로 추가하고 오답 노트하듯이 학습을 진행하는 동적인 (dynamic) 알고리즘이다.          

인간이 인생을 살며 여러 가지를 배워가는 것처럼 학습을 하는 알고리즘인 셈이다.        

대표적으로 우리가 아주 잘 아는 알파고가 강화 학습을 적용한 사례이다.       

강화 학습의 대표적인 알고리즘은 Q-Learning이 있고 딥러닝과 결합해 Deep Q Network (DQN) 방법으로도 사용되고 있다.        

​                