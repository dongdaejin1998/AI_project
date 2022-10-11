# AI_project

## 1.학습 방식 어떤 것이 있는가?

찾아본 것 
Research on Human Action Recognition in Dance Video Images 
본 논문은 학습이 아닌 춤의 특징점을 더 잘 찾아서 svm 분류기를 통해 분류의 정확도를 높이는데 의의를 둔 논문이다. svm 분류기를 사용했다.

Complex Human Action Recognition in Live Videos Using Hybrid FR-DL Method
이미지의 배경을 제거하고 HOG 기법을 통해서 전처리 후 CNNLSTM 모델을 통해서 학습 시킨다.
HOG 영상의 부분 기울기 방향 정보를 특징 벡터로 사용하는 것이다. 일반적으로 보행자 검출을 하기 위한 알고리즘을 사용된다.

HOG 관련 예시

HOG SVM 필기체 숫자 인식 예시

https://deep-learning-study.tistory.com/290

HOG 설명 예시

https://yuls-with-ai.tistory.com/310



## 2. 정성적인 평가에서 우리가 어떤걸 어필을 할 수 있을까?

미정

## 3.학습 모델은 어떤 것이 있는가?

CNN-LSTM



추가적으로 시도해본 것
mediapipe, openpose로 동영상에 적용해 봄
mediapipe는 실시간으로 동영상을 만들 수 있었으나 openpose는 실시간으로 값을 가져오는 것이 힘들었다. cpu가 아닌 gpu로 돌려서 해보는 것을 시도 중에 있다. 그러나 skeleton은 힘들다고 생각이 든다.



![openpose_발.png](https://github.com/dongdaejin1998/AI_project/blob/main/openpose_%EB%B0%9C.png?raw=true)

![mediapipe_발.png](https://github.com/dongdaejin1998/AI_project/blob/main/mediapipe_%EB%B0%9C.png?raw=true)

![mediapipe_팔.png](https://github.com/dongdaejin1998/AI_project/blob/main/mediapipe_%ED%8C%94.png?raw=true)