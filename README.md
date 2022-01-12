## Story_Maslow_Motivation_Classifier

Pre-training of BERT를 사용한 story text maslow motivation classification 모델.

#### Maslow Motivation 단계 예시

- 'Physiological_Safety' : 0
- 'Love_Esteem' : 1
- 'Cognitive_Aesthetic_Self_actualization_Transcendence' : 2

------

### Dataset

크라우드 소싱(AMT)를 통해 직접 구축한 텍스트 스토리 데이터셋

- train dataset : 총 710개 텍스트 스 토리 별 maslow 욕구 3 class 분류 태깅 데이터
- test dataset : 총 178개 텍스트 스 토리 별 maslow 욕구 3 class 분류 태깅 데이터

------

### GPU

- Colab

---------

### Task

**INPUT TEXT**

````
Bill was not in good health, started exercising every day and lost weight. Doctors said he was healthy and no longer overweight.
````

**OUTPUT**

``````
2 : Cognitive_Aesthetic_Self_actualization_Transcendence
``````

----------

Result

- 평균 F1-Score : 0.792