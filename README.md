# 포트폴리오
안녕하세요, 도담록입니다.

# 주 언어

C++, Python

# 사용 가능 언어

Flutter, C, SQL, R, CUDA C++


# C++

## Snake_Game_Player [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/blob/main/HW4/MyPlayer.cpp)

OOP를 C++로 처음 배우면서 만든 프로그램이다. 

코드의 가독성, 효율 등에 대하여 고민하지 않았고, OOP를 제대로 사용하지도 않았다.

함수를 잘 설계해서 사용하는 대신, 코드 자체를 복사, 붙여넣기하여 끔찍한 코드가 완성되었다.

![image](https://github.com/user-attachments/assets/282f7445-d17e-427c-b7fe-219ffc436c10)

이 블럭은 인수만 조금씩 바뀐 상태로 16번 가량 사용된다. 이와 비슷하게 조금씩 수정되어 반복되는 코드 블럭들이 넘치는 코드이다.

따라서 코드를 수정하기 위해서는 16번의 작업이 필요했다.

프로그램은 훌륭하게 돌아갔지만, 이러한 고칠 수도, 알아볼 수도 없는 코드를 만들지 않도록 노력하는 계기가 되었다.

## DCCP [#](https://github.com/sadgabriel/DCCP)

첫 팀 프로젝트를 하면서 만든 작곡 프로그램이다.

프로젝트에서 주도적으로 미팅을 이끌었고, 클래스 구조를 계획하였다.

![image](https://github.com/user-attachments/assets/7df52a8b-4c67-4c1b-830b-8fb23259fd36)

프로젝트의 클래스 다이어그램이다. Interface를 이용해, 외부 Printer만을 사용자에게 보여주었다.

여러 명이 동시에 작업을 하면서 충돌이 생기지 않도록 네이밍 컨벤션, 코딩 스타일에 대한 합의도 진행하였다.

프로젝트에서 팀원 간의 소통의 중요성을 느낀 프로젝트였다. 처음에는 팀원들끼리 무엇을 얼마나 진행했고, 어디가 문제인지 공유가 되지 않아 프로젝트 진행이 굼떴다.

팀원들끼리 잦게 주기적 회의를 하여 이 문제는 해결되었고, 이후로도 다른 프로젝트들에서도 진행 상황 등에 대한 이야기를 나눌 수 있는 회의를 주도적으로 제안하는 습관이 생겼다.

# C

## 2D Convolucion Optimize  [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/tree/main/systemprogramming_optimize)

C++ 파일을 컴파일할 때 자동으로 최적화를 해주는 옵션을 끄고, 기본적인 2D convolution 프로그램 [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/blob/main/systemprogramming_optimize/proj.c)을 최적화하는 과제였다.

Loop unrolling, 조건문 순서 수정 등을 사용하는 과제였지만, CPU의 캐시 지역성을 생각해 알고리즘을 다시 설계하였다.

나의 로컬 컴퓨터의 CPU와 서버 CPU가 달랐기 때문에, 캐시의 크기와 구조가 달랐다. 따라서, 최고의 효율을 보이는 블록 크기가 다른 값이 나오는 것을 확인하였다.

후에 CUDA를 공부하면서도, GPU의 구조에 따라 사용하는 최적의 알고리즘이 다르다는 것을 배웠고, 서버의 하드웨어를 고려한 프로그래밍이 필요하다는 것을 알았다.

# 인공지능

## 강화학습

### 점진적인 환경 변화 실험  [#](https://github.com/ehekafhr/TStarBot1)

스타크래프트2의 PPO를 이용한 인공지능 중 하나인 Tstarbot1을 변형하여, 이미 학습된 Tstarbot에서

APM(Action Per Minute)에 제약을 가할 때, 바로 제약을 가하여 재학습시킨 모델과 재학습 도중에 제약을 천천히 추가해 나간 모델을 비교하였다.

실험 결과, 재학습 도중에 제약을 천천히 추가해 나간 모델의 성능이 더 우수했다.

공개된 거대한 코드를 팀원들과 분석하고 이해하는 것이 힘든 시간이었다. 우리의 목적에 맞게 코드를 수정하기 위해서는 먼저 코드를 이해해야 했고, 우리가 수정한 코드가 우리가 원한 대로 동작하는지 확인하기 위해 서버가 아닌 로컬 컴퓨터에도 실험 환경을 세팅하고, 게임 화면을 관찰해야 했다. 

실험에서 도출된 결과뿐만 아니라, 타인의 코드 구조를 이해하는 능력 또한 기른 프로젝트였다.

## 딥 러닝

### 인공지능경진대회 참여(언어 모델)

법률 문서 요약 부문에서, 학습의 효율성을 높이기 위해 데이터 전처리를 하는 역할을 맡았다.

굉장히 휴리스틱하게, 특정 문장이나 특정한 특수 기호 등의 나타남 등을 이용하여 몇 데이터들을 먼저 분류하였다.

[대회참가인증서](https://github.com/user-attachments/files/18141398/default.pdf)


### Numpy를 이용한 NN과 CNN 구현 [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/tree/main/%EB%94%A5%EB%9F%AC%EB%8B%9D%EA%B0%9C%EB%A1%A0/PA1_201911050_%EB%8F%84%EB%8B%B4%EB%A1%9D)

Pytorch, Tensorflow 등의 딥러닝 프레임워크를 사용하지 않고, Numpy를 이용하여 행렬곱을 이용해 Forward, Backward propagation을 구현해 NN과 CNN을 구현하였다.

![image](https://github.com/user-attachments/assets/62cacd07-c9ee-47ce-872d-a11847f9806d)

MNIST dataset에 대해 93-97% 정도의 정확도가 나왔다. 전처리로 Histogram normalization 등을 사용해 보았지만, 유의미할 정도의 정확도 향상을 보지는 못했다.

직접 NN과 CNN을 구현해 보고, Pytorch를 이용해 보니 변수 관리




### Flutter를 이용한 앱 개발 [#](https://github.com/ehekafhr/od_ugrp_ehekafhr)

Yolov5 모델을 이용하여 데이터 수집, 전이학습, Torchlite 경량화, Flutter로 휴대폰 어플리케이션에 이식을 진행한 프로젝트이다.

# 학력

DGIST 기초학부(2019-2023) (컴퓨터공학 전공 인정)

[전공 인정 확인서](https://github.com/user-attachments/files/18141400/201911050.pdf)

# 자격증

-정보처리기사

-SQLD

-TOEIC LC/RC 835

# [BOJ](https://www.acmicpc.net/user/ehekafhr)

# 연락
ehekafhr@naver.com
