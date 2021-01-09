# Fall-dectection
노인 낙상 감지 시스템

● 라즈베리파이와 파이카메라를 사용

![raspberry](https://user-images.githubusercontent.com/61223256/104096280-e994ea00-52de-11eb-95ae-ab803c111830.png)

● 인물 인식
  라즈베리파이와 파이카메라를 이용하여 openCv의 thresehold와 contour함수를 사용하여 동적인 물체를 이진화, 감지함.

 ![영상이진화](https://user-images.githubusercontent.com/61223256/104096293-029d9b00-52df-11eb-9d5f-13bc6b78ff24.png)

  boundingRect 함수로 사람을 인식. 낙상 시, boundingRect가 초록색에서 빨간색으로 변함.
  
  
