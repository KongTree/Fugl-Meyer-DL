# tf-fugl-meyer

## 개요


    딥러닝에 대하여 공부를 한 후 mnist, cifar10을 가지고 체험을 해보고나서 처음으로 직접 주제를 정하여 진행하게되었습니다.


## 사용언어 및 기술
    Tensorflow, Python, Fugl-Meyer(관련 논문)


## 설명
    Fugl-Meyer (치매 치료 정도 측정) 차트를 베이스로 하여 팀원의 의견을 종합하여 학습하고자 하는 행동을 정하여 데이터 수집 좌/우 같은 행동의 데이터를 모았음(약 2만여장), 참여자 수 (15명)
    
    이렇게 모은 데이터들을 우리가 만든 학습신경망을 이용하여 학습을 진행, 웹 카메라를 사용하여 실시간으로 테스트 진행(OpenCV를 활용)
    
## 결과
    학습시킨 행동들 중 유사한 행동이 보일 경우 정확도가 약간씩 뒤틀림
    어느정도 학습시킨 행동들은 높은 정확도를 보여줌
    
## 보안
