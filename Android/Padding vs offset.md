Android의 Jetpack compose 라이브러리의 대한 내용입니다

둘의 공통점은 모두 자식 요소를 움직이게 한다는 점이다. 하지만 요소를 움직여 맞추려고 할 때 차이점이 생긴다.

# Padding

padding 자식 요소를 신경쓰지 않고 부모와의 거리를 만든다.

만약 **자식 요소와 설정한 padding 값이 부모 요소의 크기**보다 크다면 자식 요소는 **원본 크기를 유지하지 않고 줄어**든다.

# Offset

offset은 padding과 마찬가지로 자식 요소와의 거리를 원하는 만큼 설정할 수 있다. 하지만 아무리 자식 요소보다 큰 값이 들어가도 자식 요소가 **원본 크기를 유지**한다. 
