# Obsidian template for using github.io
**<1주차(2024.07.07)>**
-파이토치(PyTorch):
  파이썬 러닝 라이브러리.
  파이토치 특징1. Numpy와 유사하지만 GPU 상에서 실행 가능한 n차원 Tensor.
  파이토치 특징2. 신경망을 구성하고 학습하는 과정에서 자동 미분.
-CNN(Convolutional Neural Network):
  입력된 이미지를 "합성곱" 연산을 중심으로 분석한 뒤, 이 데이터를 한 줄로 편 다음(flatten) 복잡하게 얽히고 연결된 신경망에 넣어 이미지를 "확률론적으로" 인식.
  이미지와 같은 멀티미디어에 강함.
-RESNET(Residual Neural Network):
  152개의 층을 가지는 구조.
  레이어의 input이 다른 리이어로 곧바로 건너뛰어버리는 것이 특징.
  입력값들이 중간의 특정 레이어를 모두 거치지 않고 한번에 건너뛴다는 의미.
  VggNet을 베이스로 했으며, 지름길(Shortcut)을 연결해 잔차(Residual)를 최소화하도록 학습됨.