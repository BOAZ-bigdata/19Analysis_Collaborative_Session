# PyTorch와 TensorFlow
2022-2 BOAZ 분석 공동세션, 12/29(목), 18기 분석 박규연

## Contents
- PyTorch and TensorFlow
- Code Comparison
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

## Code Comparison
### Static vs Dynamic
- Define and Run : 그래프 정의 후 실행 시 데이터 입력
- Define by Run : 실행하면서 그래프 정의 및 데이터 입력
### Network, Training
- TensorFlow: 변수 형태
- PyTorch: 클래스 형태


## PyTorch vs TensorFlow
- 모델 가용성 -> PyTorch
- 배포 인프라 -> TensorFlow
- 생태계

## Conclusion
- 산업, IoT, 모바일 디바이스 -> TensorFlow
- SOTA 모델 액세스 -> PyTorch

***

Notion | https://www.notion.so/PyTorch-TensorFlow-7c9ecd35f56f41a8a9609ae0d1cfbc37
