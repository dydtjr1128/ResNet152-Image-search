# ResNet152-Image-search
ResNet152 Image search using Tenserflow



<p align="center">
  <img src="https://user-images.githubusercontent.com/19161231/47410560-25e0dc00-d7a1-11e8-8f66-dbe2e4052087.png">
</p>

ResNet에 관한 내용을 찾아보면서 이미지 탐지 오류율 3.57%의 ResNet152, 152개의 레이어를 이용한 모델을 사용하였다.
사용을 위해 모델을 불러오는 코드를 작성하였다.


<p align="center">
  <img src="https://user-images.githubusercontent.com/19161231/47410567-2b3e2680-d7a1-11e8-8924-6f98c4a4c771.png">
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/19161231/47410570-2ed1ad80-d7a1-11e8-8340-f622ca1c1ef6.png">
</p>
각각의 ResNet 모델별 레이어 구성 인자가 다르므로 그 부분은 다른 숫자 리스트를 입력한다.

<p align="center">
  <img src="https://user-images.githubusercontent.com/19161231/47410578-3729e880-d7a1-11e8-881f-5c1fee7bb3d1.png">
</p>
224의 해상도를 가진 이미지들을 이용하여 resnet152 모델로 분류한다.
