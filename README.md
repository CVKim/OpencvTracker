# OpencvTracker 

// Video Dataset

https://www.pexels.com/videos/



![image](https://user-images.githubusercontent.com/90014998/164339638-6f4c342a-24a5-4927-8903-1fb2c1098442.png)


1. VideoCapture 함수를 통해 동영상 File Load
2. read 함수를 통해 배경 영상 받음
3. cv2Color, GaussianBlur 함수를 통해 전처리
4. 한 프레임씩 받아서 이미지 차 연산
5. labeling을 위한 bb에 대한 정보 받아옴
6. 최소 27Pixel 이하는 무시하고 그 이상만 labeling 표시
7. 동영상 프레임 종료 전까지 반복


// accumulateWeighted 함수를 통해 이동 평균 계산 / 가중치 누적

![image](https://user-images.githubusercontent.com/90014998/164339994-2a1c086f-9019-4e6f-baea-6e1dd16da4af.png)

// 바운딩 박스 표시 

![image](https://user-images.githubusercontent.com/90014998/164339947-e5dc4b52-9e9c-408d-9f56-883dcc6c01e3.png)
