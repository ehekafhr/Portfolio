# 소개

안녕하세요, 도담록입니다.

---
# 주 언어

C: 시스템 프로그래밍

C++: 객체지향 프로그래밍

Python: 데이터 분석, 인공지능
---
# 사용 가능 언어

Flutter: 모바일 앱 개발

SQL: 데이터베이스 서례, 쿼리 작성

CUDA C++: GPU 프로그래밍

# 프로젝트
	
## C++
	
### Snake_Game_Player [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/blob/main/HW4/MyPlayer.cpp)
	
OOP를 C++로 처음 배우면서 만든 프로그램입니다. 
	
함수를 잘 설계해서 사용하지 않고, 코드 자체를 복사 붙여넣기하여 가독성이 좋지 않은 코드가 되었습니다..
	
![image](https://github.com/user-attachments/assets/282f7445-d17e-427c-b7fe-219ffc436c10)

이 코드는 여러 번 반복된 코드 블록입니다. 유지보수성이 굉장히 떨어졌고, 코드의 가독성과 효율성에 대해 고민하게 되었습니다.

이 프로그램은 훌륭하게 돌아갔지만, 이러한 고칠 수도, 알아볼 수도 없는 코드는 그 당시의 제가 보기에도 좋지 않았고, 모듈화와 OOP에 신경을 쓰게 되었습니다.

### DCCP [#](https://github.com/sadgabriel/DCCP)

첫 팀 프로젝트를 하면서 만든 작곡 프로그램입니다.

팀 프로젝트에서 미팅을 주도적으로 이끌고, 클래스 구조를 설계하였습니다.

팀원 간 작업 시의 충돌을 방지하기 위해, 네이밍 컨벤션과 코딩 스타일에 대한 합의를 도출하였고, 프로젝트가 진행하는 데에 중요한 역할을 했습니다.

프로젝트에서 팀원 간의 소통의 중요성을 느낀 프로젝트였습니다. 처음에는 팀원들끼리 무엇을 얼마나 진행했고, 어디가 문제인지 공유가 되지 않아 프로젝트 진행이 굼떴습니다.

팀원들끼리 잦게 주기적 회의를 하여 이 문제는 해결되었고, 이후로도 다른 프로젝트들에서도 진행 상황 등에 대한 이야기를 나눌 수 있는 회의를 주도적으로 제안하는 습관이 만들어졌습니다.

## C

### 2D Convolucion Optimize  [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/tree/main/systemprogramming_optimize)

C++ 파일을 컴파일할 때 자동으로 최적화를 해주는 옵션을 끄고, 기본적인 2D convolution 프로그램 [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/blob/main/systemprogramming_optimize/proj.c)을 최적화하는 과제였다.

Loop unrolling, 조건문 순서 수정 등을 사용하는 과제였지만, CPU의 캐시 지역성을 생각해 알고리즘을 다시 설계하였다.

나의 로컬 컴퓨터의 CPU와 서버 CPU가 달랐기 때문에, 캐시의 크기와 구조가 달랐다. 따라서, 최고의 효율을 보이는 블록 크기가 다른 값이 나오는 것을 확인하였다.

후에 CUDA를 공부하면서도, GPU의 구조에 따라 사용하는 최적의 알고리즘이 다르다는 것을 배웠고, 서버의 하드웨어를 고려한 프로그래밍이 필요하다는 것을 알았다.

## 인공지능

### 강화학습

#### 점진적인 환경 변화 실험  [#](https://github.com/ehekafhr/TStarBot1)

스타크래프트2의 PPO를 이용한 인공지능 중 하나인 Tstarbot1을 변형하여, 이미 학습된 Tstarbot에서

APM(Action Per Minute)에 제약을 가할 때, 바로 제약을 가하여 재학습시킨 모델과 재학습 도중에 제약을 천천히 추가해 나간 모델을 비교하였다.

실험 결과, 재학습 도중에 제약을 천천히 추가해 나간 모델의 성능이 더 우수했다.

공개된 거대한 코드를 팀원들과 분석하고 이해하는 것이 힘든 시간이었다. 우리의 목적에 맞게 코드를 수정하기 위해서는 먼저 코드를 이해해야 했고, 우리가 수정한 코드가 우리가 원한 대로 동작하는지 확인하기 위해 서버가 아닌 로컬 컴퓨터에도 실험 환경을 세팅하고, 게임 화면을 관찰해야 했다. 

실험에서 도출된 결과뿐만 아니라, 타인의 코드 구조를 이해하는 능력 또한 기른 프로젝트였다.

### 딥 러닝

#### 인공지능경진대회 참여(언어 모델)

법률 문서 요약 부문에서, 학습의 효율성을 높이기 위해 데이터 전처리를 하는 역할을 맡았다.

굉장히 휴리스틱하게, 특정 문장이나 특정한 특수 기호 등의 나타남 등을 이용하여 몇 데이터들을 먼저 분류하였다.

[대회참가인증서](https://github.com/user-attachments/files/18141398/default.pdf)


#### Numpy를 이용한 NN과 CNN 구현 [#](https://github.com/ehekafhr/DGIST_ASSIGNMENTS/tree/main/%EB%94%A5%EB%9F%AC%EB%8B%9D%EA%B0%9C%EB%A1%A0/PA1_201911050_%EB%8F%84%EB%8B%B4%EB%A1%9D)

Pytorch, Tensorflow 등의 딥러닝 프레임워크를 사용하지 않고, Numpy를 이용하여 행렬곱을 이용해 Forward, Backward propagation을 구현해 NN과 CNN을 구현하였다.

![image](https://github.com/user-attachments/assets/62cacd07-c9ee-47ce-872d-a11847f9806d)

MNIST dataset에 대해 93-97% 정도의 정확도가 나왔다. 전처리로 Histogram normalization 등을 사용해 보았지만, 유의미할 정도의 정확도 향상을 보지는 못했다.


#### Flutter를 이용한 상점에서의 Object Detection 앱 개발 [#](https://github.com/ehekafhr/od_ugrp_ehekafhr)

Yolov5 모델을 이용하여 데이터 수집, 전이학습, Torchlite 경량화, Flutter로 휴대폰 어플리케이션에 이식을 진행한 프로젝트이다.

상점 이미지에서 먼저 상품군을 찾아내고, 상품군 내에서 OCR을 진행하는 어플리케이션이다.

##### 데이터 수집

Roboflow에서 해외의 상점 이미지들을 이용해 서버에서 모델을 학습시키고 한국의 데이터를 test set으로 했을 때 정확도가 극단적으로 떨어지는 문제가 생겼다.

외국 상점들의 상품군 배치와 우리나라의 상품군 배치가 상이해, 오히려 소량의 직접 수집한 한국 데이터만을 사용해 학습했을 때보다 정확도가 떨어졌다.

원하는 데이터가 정확히 한국 상점의 데이터인 것을 확인하고, 학습하기에 충분한 데이터를 직접 사진을 찍어 수집했다.

##### 전이학습과 경량화

학습된 Yolov5 모델에서 마지막 단을 교체하고 나머지 weight을 freezing하여 전이학습을 진행하고, torchlite로 경량화를 진행하였다.

실수로 weight 고정을 풀고 학습시킨 적이 있는데, 모델의 크기에 비해 데이터가 부족해 엄청난 overfitting이 발생하였다.

##### Flutter을 이용한 애플리케이션 개발

Flutter에는 Pytorch package가 있기 때문에, 어플리케이션 개발은 Flutter을 통해 진행되었다.

복잡한 기능 구현 없이 카메라 사용, 슬라이드 등으로 OCR / Object detection 모드 전환 등의 기능을 구현하였다. 

##### 바코드 인식

상품의 바코드를 인식하여 상품 정보를 보여주는 기능을 제공한다.

최신 바코드 데이터 API의 경우는 문의 후 결제를 해야 사용 가능했기에, 2019년까지의 데이터(애플리케이션 개발은 2023년이다)만을 제공하는 다른 API에 연결해서 바코드 인식이 제대로 동작하는 것을 확인하였다.

# 학력

DGIST 기초학부(2019-2023) (컴퓨터공학 전공 인정)

[전공 인정 확인서](https://github.com/user-attachments/files/18141400/201911050.pdf)

# 자격증

-정보처리기사

-SQLD

-TOEIC LC/RC 835

# 백준 온라인 저지 (BOJ)
[프로필](https://www.acmicpc.net/user/ehekafhr)
Graph, Greedy algorithm, 구현, Dynamic programming 등 문제 해결과 최적화, 구현을 위주로 실력을 쌓았습니다.

# 연락
ehekafhr@naver.com
