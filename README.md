## CNN Visualization Techique From Scratch


### Objective

CNN은 대표적인 Black Box 모형입니다. 영상의 어떤 특징이 모델의 결과를 결정했는지를 알기 어렵습니다. 이러한 모형의 특징은 모델의 결과에 대한 신뢰성에도 악 영향을 미칩니다.

이러한 문제는 다양한 해결책들이 제시되어 왔는데, 대표적으로 Filter Visualization / Grad-CAM / Guided Backpropagation(Guided Grad-CAM)을 보도록 하겠습니다.


### 구성

모든 코드는 `scripts/`에 수록되어 있습니다.

1. Filter Visualization
2. Grad-CAM
3. Guided Back-Propagation

