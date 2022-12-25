# PyTorch와 TensorFlow
2022-2 BOAZ 분석 공동세션, 12/29(목), 18기 분석 박규연

## Contents
- PyTorch and TensorFlow
- PyTorch vs TensorFlow
- Conclusion

***

## PyTorch and TensorFlow

### TensorFlow
Google이 개발한 오픈소스 머신러닝 라이브러리
- 데이터 플로우 그래프(Data Flow Graph)를 통한 풍부한 표현력
- 연산 구조와 목표 함수만 정의하면 자동으로 미분 계산(Automatic differentiation)
### PyTorch
FaceBook이 개발한 오픈소스 머신러닝 라이브러리
- NumPy와 유사하지만 GPU 상에서 실행 가능한 n-차원 텐서(Tensor)
- 신경망을 구성하고 학습하는 과정에서의 자동 미분

### 프레임워크를 사용하는 이유
- 복잡한 연산 그래프를 쉽게 빌드하기 위해
- 그래디언트 계산을 쉽게 하기 위해
- GPU를 효율적으로 사용하기 위해

## PyTorch vs TensorFlow
### Static vs Dynamic
- Define and Run : 그래프 정의 후 실행 시 데이터 입력
- Define by Run : 실행하면서 그래프 정의 및 데이터 입력
### 고려사항
- 모델 가용성 -> PyTorch
- 배포 인프라 -> TensorFlow
- 생태계 -> TensorFlow

## Conclusion
- 산업, IoT, 모바일 디바이스 -> TensorFlow
- SOTA 모델 액세스 -> PyTorch
