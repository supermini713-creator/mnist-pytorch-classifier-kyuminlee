# mnist-pytorch-classifier-kyuminlee
1. 프로젝트 소개
   코드로 신경망을 구현하는 것 중 혼자 할 수 있는 가장 간단한 프로젝트가 무엇일까 찾아보다, Udacity에 있는 <iNTRO TO DEEP LEARNING WITH PYTORCH> 강좌의 내용을 바탕으로
   프로젝트를 진행하게 되었습니다. 이 코드는 딥러닝 프레임워크인 PyTorch를 사용하여, 대표적인 이미지 데이터셋인 MNIST에서 손글씨 이미지를 학습하고 그 뒤에 숫자를 분류해 내는
   인공 신경망을 구현한 것입니다. <데이터 준비 -> 모델 설계 -> 훈련 -> 평가>의 구조로 이루어져 있습니다.

2. 모델 구조
   Input Layer: 784
   HIdden Layer 1: 128, ReLU activation function
   HIdden Layer 2: 64, ReLU activation function
   Output Layer: 10

3. 결과
   Test data final accuracy(1st try) : 96.12%
    Epoch 1 - Training loss:0.34695969698732215
    Epoch 2 - Training loss:0.1767930956358817
    Epoch 3 - Training loss:0.14067351746895135
    Epoch 4 - Training loss:0.11974137074856171
    Epoch 5 - Training loss:0.11460407637878815
    accuracy: 95.65%
    Epoch 6 - Training loss: 0.10593774038077051
    Epoch 7 - Training loss: 0.09546197244975922
    Epoch 8 - Training loss: 0.09334922901569193
    Epoch 9 - Training loss: 0.08401221834864817
    Epoch 10 - Training loss: 0.08562025612941
    Final Accuracy: 96.12%
   
   Test data final accuracy(2nd try) : 96.74%
   Epoch 1 - Training loss:0.34471023666944456
   Epoch 2 - Training loss:0.17309683179661536
   Epoch 3 - Training loss:0.14287944424694884
   Epoch 4 - Training loss:0.12663107921532207
   Epoch 5 - Training loss:0.11419610164042857
   accuracy: 96.82%
   Epoch 6 - Training loss: 0.10121360432574036
   Epoch 7 - Training loss: 0.09657535877630813
   Epoch 8 - Training loss: 0.08856718504735862
   Epoch 9 - Training loss: 0.08994183469109976
   Epoch 10 - Training loss: 0.08300378324439389
   Final Accuracy: 96.74%

5. 사용한 프로그래밍 도구
   Python (언어)
   PyTorch (프레임워크)
   Numpy (라이브러리)
   
