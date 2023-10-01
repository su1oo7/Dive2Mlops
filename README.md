
## Tensorflow extended Tutorial 

- 박찬성님의 [github repo](https://github.com/deep-diver/semantic-segmentation-ml-pipeline)를 
참고하여 간단한 모델의 tfx 활용 pipeline을 구축하는 repository
- 진행하며 dataset, model은 변경 될 수 있으나 최대한 milestone의 진행 step을 각 단계의 deadline으로 간주하여 진행
- milestone의 각 step은 3일이며 총 30일 10월 21일까지 진행되는 project.

### 1.Dataset 
**Lung Segmentation on CT**
- For our model, we utilize a publicly available dataset from the IRCAD research center in France, containing 20 annotated 3D CT series. We split this dataset into 15 for training/validation and 5 for testing. You clone it from [the GitHub repository](https://github.com/rekalantar/CT_LiverSegmentation).

### 2. Model
**Deeplab v3+ / U-net**
  

### 3. Milestone
각 step은 3일의 간격을 나타내고 있음
(E: Expected, O: Done, X: Failed)
|task|1|2|3|4|5|6|7|8|9|10|
|--|--|--|--|--|--|--|--|--|--|--|
|reference 숙지 |X|O|E|E|||||||
|base 모델 test |X|O|||||||||
|base 모델 py 구조화 ||||E|||||||
|ExampleGen 구현 |X|X|E||||||||
|SchemaGen 구현 |X|X|E||||||||
|Transform 구현 ||X|E||||||||
|Trainer 구현 ||X|E|E|E||||||
|Evaluator 구현 ||||||E|E||||
|Pusher 구현 |||||||E|E|E||
|repository 정리 ||||E|||||E|E|


    
