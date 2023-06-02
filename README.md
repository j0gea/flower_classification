# flower_classification
### 파일 정리

- flower : 메인 코드(기본) (혹은 세 모델 모두 여기에 넣어서 정리해도 괜찮다)
- flower_모델 이름 : 각 모델의 코드 (그 모델의 코드만) ex: flower_resnet101, flower_resnet50

---

## 모델 정리 표

|모델/컨디션|컨디션1|컨디션2|
|------|---|---|
|모델1|정확도|정확도|
|모델2|정확도|정확도|
|모델3|정확도|정확도|

- 정확도가 괜찮거나 특이점이 있는 모델은 따로 파일로 뽑아 링크 걸어두기
- 링크거는 법 : [표시할 내용] (링크)

ex

|모델/컨디션|V2 100 B10 E20 EX|V2 100 B64 E50 EO|V2 100 B64 E50 EX|V2 64 B64 E50 EO|
|------|---|---|---|---|
|resnet101|42.76 %|36.985 %|44.374 %|29.512 %|

|모델/컨디션|*V2* 200 B64 E50 EO|V1 224 B64 E50 EO|V1(8) 100 B64 E50 EO|
|------|---|---|---|
|resnet50v2|77.707 %|88.272 %|88.063 %|

---

## 수정 이력

### 2023-06-02 BETA

#### 수정해야 할 부분

- 데이터 늘리기 수정 (RAM을 너무 많이 잡아먹기 때문에 한 텀 끝나고 다음 텀을 실행할 수 있게 쪼개기)
- tfrecords로 파일을 불러들이는 부분 추가(코드는 있으나 정리 필요)
- 기타 자잘한 부분 수정 및 최적화(필요없는 부분 수정)


**참고 자료**

- [How to use the Kaggle API from Colab](https://colab.research.google.com/github/corrieann/kaggle/blob/master/kaggle_api_in_colab.ipynb)
- [image to dataset](https://github.com/letddo/flower_classification/blob/main/flower.ipynb)
