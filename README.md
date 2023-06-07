# flower_classification
### 파일 정리

- flower : 메인 코드(기본) (혹은 세 모델 모두 여기에 넣어서 정리해도 괜찮다)
- flower_모델 이름 : 각 모델의 코드 (그 모델의 코드만) ex: flower_resnet101, flower_resnet50

---

## 모델 정리 표

https://docs.google.com/spreadsheets/d/17olBml7qZoqZdUS6x3oNvyLL7GxbvkrQra46ukBNZeM/edit?usp=sharing

---

## 수정 이력

### 2023-06-02 BETA

#### 수정해야 할 부분

- 데이터 늘리기 수정 (RAM을 너무 많이 잡아먹기 때문에 한 텀 끝나고 다음 텀을 실행할 수 있게 쪼개기)
- tfrecords로 파일을 불러들이는 부분 추가(코드는 있으나 정리 필요)
- 기타 자잘한 부분 수정 및 최적화(필요없는 부분 수정)

### 2023-06-07

- 웹 크롤러 추가(pixabay)
- 이미지 분류기 추가

**참고 자료**

- [How to use the Kaggle API from Colab](https://colab.research.google.com/github/corrieann/kaggle/blob/master/kaggle_api_in_colab.ipynb)
- [image to dataset](https://github.com/letddo/flower_classification/blob/main/flower.ipynb)
