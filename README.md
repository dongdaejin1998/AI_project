# AI_project

## 1.학습 방식 어떤 것이 있는가?

찾아본 것 
Research on Human Action Recognition in Dance Video Images 
본 논문은 학습이 아닌 춤의 특징점을 더 잘 찾아서 svm 분류기를 통해 분류의 정확도를 높이는데 의의를 둔 논문이다. svm 분류기를 사용했다.

Complex Human Action Recognition in Live Videos Using Hybrid FR-DL Method
이미지의 배경을 제거하고 HOG 기법을 통해서 전처리후 CNN-LSTM 모델을 통해서 학습 시킨다.
HOG 영상의 부분 기울기 방향 정보를 특징 벡터로 사용하는 것이다. 일반적으로 보행자 검출을 하기위한 알고리즘을 사용된다.

## 2. 정성적인 평가에서 우리가 어떤걸 어필을 할 수 있을까?

아직 생각중에 있다. 가장 중요한 것이라고생각은하나 어렵기에 변명거리 뿐이다.하하
추가 숙제 :정성과 정량 알아보기

## 3.학습 모델은 어떤 것이 있는가?

CNN-LSTM

![mediapipe_발사위.png](https://github.com/dongdaejin1998/AI_project/blob/main/mediapipe_%EB%B0%9C%EC%82%AC%EC%9C%84.png?raw=true)

![mediapipe_팔사위.png](https://github.com/dongdaejin1998/AI_project/blob/main/mediapipe_%ED%8C%94%EC%82%AC%EC%9C%84.png?raw=true)

![openpose_발사위.png](https://github.com/dongdaejin1998/AI_project/blob/main/openpose_%EB%B0%9C%EC%82%AC%EC%9C%84.png?raw=true)



추가적으로 시도해본 것
mediapipe,openpose로 동영상에 적용해봄 
mediapipe는 실시간으로 동영상을 만들 수 있었으나 openpose는 실시간으로 값을 가져오는 것이 힘들었다. cpu가 아닌 gpu로 돌려서 해보는 것을 시도중에 있다. 그러나 skeleton은 힘들다고 생각이 든다.