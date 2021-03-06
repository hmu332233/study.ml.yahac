## 지도학습 - 회귀 regression

### Neural Network <- 수업대상
- 사람처럼 학습을 할 수 있도록 고안된 알고리즘
- 인간의 신경을 모방

---

### 지도학습의 작업 순서

1. 과거의 데이터를 준비
2. 모델의 모양을 만들기
  - 원인의 열이 n개, 결과의 열이 m개
3. 데이터로 모델을 학습 시킴 (FIT)
4. 모델을 이용


---

### 모델이란
`y = a*x + b`
- 독립 변수와 종속 변수의 관계를 설명해주는 a와 b의 값을 찾는 것.
- a: 가중치 weight
- b: 편향 bias
- 가중치와 편향을 합쳐서 가중치라고 하기도 함
- x가 여러개라면
  - `y = a*x1 + b*x2 ... + c`


---

## 딥러닝

- perceptron: 뉴런이 나타내는 것을 모방해서 만든 것  (y1 = a * x1 + b * x2 ... c)
- ANN: 뇌처럼 뉴런들이 연결된 것과 같이 perceptron을 연결해서 만든 것을 Artificial Neural Network이라한다.
- perceptron 깊게 연결해서 문제를 해결하는 기술을 Depp learning이라 한다.

- node: 값을 나타내는 것 하나하나를 지칭
- layer: node들의 그룹
- input layer: 모델로 입력을 받는 layer
- output layer: 모델에 의해 연산된 값을 출력하는 layer
- hidden layer: input layer와 output layer 사이에 존재하는 layer

![image](images/deeplearning.png)