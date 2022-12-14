# TensorFlow

![tensorflow_logo_icon_170598](https://user-images.githubusercontent.com/112846155/202891105-143c327b-2eb0-48dc-83d2-5d1756be2a2c.png)

<br>

## 1. Tensorflow란?
**구글에서 만든 기계 학습(딥러닝/머신)을 위한 오픈소스 라이브러리.**
> 딥러닝과 기계학습 분야를 일반인들도 사용하기 쉽도록 다양한 기능들을 제공하여 전 세계적으로 가장 인기 있고 많이 쓰이는 기계 학습 라이브러리이다. 

<br>

## 2. 특징
- 데이터 플로우 그래프를 통한 풍부한 표현력
- 아이디어 테스트에서 서비스 단계까지 이용 가능
- 계산 구조와 목표 함수만 정의하면 자동으로 미분 계산을 처리
- Python, C++, Go, Java, R을 지원하며, SWIG를 통해 다양한 언어 지원 가능

<br>

3. 역사
### DistBelief
2011년부터 구글 브레인 팀은 첫 머신러닝 시스템으로 DistBelief를 만들었다. 구글에 있는 50개가 넘는 팀과 모회사 알파벳에서 검색, 음성검색, 광고, 구글 포토, 구글 맵스, 스트리트뷰, 번역, 유튜브 등 같은 실제 서비스에 디스트빌리프의 딥 러닝 인공 신경망이 적용되었다.

### Tensorflow
Tensorflow는 2015년에 오픈 소스로 공개된 구글 브레인 팀의 두 번째 머신 러닝 시스템이다. TensorFlow는 안드로이드와 iOS같은 모바일 환경은 물론 64비트 리눅스, macOS의 데스크탑이나 서버 시스템의 여러개의 CPU와 GPU에서(GPU에서 일반 연산을 수행하게 하는 CUDA 확장기능을 사용) 구동될 수 있다. 텐서플로 연산은 상태를 가지는 데이터 흐름(stateful dataflow) 유향 그래프로 표현된다. 구글에 있는 많은 팀이 연구와 제품 개발을 위해 디스트빌리프에서 텐서플로로 이전했다.

<br>

## 4. 버전
```
공개된 버전은 일반 버전과 GPU 가속 버전 두 가지이다. 일반 버전은 어떤 컴퓨터에서든 실행할 수 있다는 장점이 있다.
GPU 가속 버전은 GPGPU를 사용해 대량 연산을 빠르게 수행하므로 훨씬 빠르게 동작하게 된다
현재 NVIDIA의 GPGPU 언어인 CUDA를 사용하기 때문에 NVIDIA 그래픽카드가 없으면 사용할 수 없다. GPU 가속 버전의 성능은 CPU 성능과는 별 관계가 없고 GPU 성능이 중요하다.
CUDA 드라이버와 cuDNN 드라이버를 추가적으로 설치하여야 한다.
TensorFlow 2.0이 출시되면서 CPU 버전과 GPU 버전이 통합되었다. CUDA 환경 설치가 올바르게 되었다면 자동으로 GPU를 인식해준다.
```
