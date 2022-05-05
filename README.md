# 퀵소트 알고리즘 소요시간 분석

## 오름차순 정렬된 배열

2^n 개의 원소를 가지는 배열을 오름차순 시켜두고 피벗값을 배열의 중간값으로 잡는 방식을 사용한다.   
이때의 결과는   
https://user-images.githubusercontent.com/102293576/166910823-444592ca-6f2d-4141-b425-ac469475d774.png   
   
위 사진과 같다. 이를 그래프로 표현하면   
https://user-images.githubusercontent.com/102293576/166913299-92039686-4dfc-4b4b-a3a8-6de96b6d6d84.png   



## 랜덤 정렬된 배열

2^n 개의 원소를 가지는 배열을 셔플 시켜두고 피벗값을 배열의 중간값으로 잡는 방식을 사용한다.   
이때의 결과는   
https://user-images.githubusercontent.com/102293576/166910891-f79b0ea8-9434-493e-afc2-dd9e0864b05e.png   
   
위 사진과 같다. 이를 그래프로 표현하면   
https://user-images.githubusercontent.com/102293576/166913321-e867570b-f886-4214-b2fb-c71edcea81f6.png   



## 내림차순 정렬된 배열

2^n 개의 원소를 가지는 배열을 오름차순 시켜두고 피벗값을 배열의 중간값으로 잡는 방식을 사용한다.   
이때의 결과는   
https://user-images.githubusercontent.com/102293576/166910917-85c099ec-5573-45b6-a2e4-e0d0e1f37946.png   
   
위 사진과 같다. 이를 그래프로 표현하면   
https://user-images.githubusercontent.com/102293576/166915247-bdf8459f-d30d-4de6-8039-205875e9056a.png

## 배열 별 소요시간 모아보기
   
위 소요시간 그래프를 하나로 모으면    
   
https://user-images.githubusercontent.com/102293576/166913325-65ae3b28-c1b3-4e44-b6e3-a3a5a9644e1c.png   
   
오름차순, 내림차순의 소요시간이 거의 일치하는 것을 볼 수 있다. 피벗이 중앙값으로 설정되어서 그럴 것이라 예상이 가능하다..   
랜덤하게 배열된 경우 오름, 내림차순보다 시간이 더 소요됨을 알 수 있다.   

