
## Tensorflow extended Tutorial 

- 박찬성님의 [github repo](https://github.com/deep-diver/semantic-segmentation-ml-pipeline)를 
참고하여 간단한 모델의 tfx 활용 pipeline을 구축하는 repository
- 진행하며 dataset, model은 변경 될 수 있으나 최대한 milestone의 진행 step을 각 단계의 deadline으로 간주하여 진행
- milestone의 각 step은 3일이며 총 30일 10월 21일까지 진행되는 project.

### 1.Dataset 
**PACS (Photo-Art-Cartoon-Sketch)**
- PACS is an image dataset for domain generalization. It consists of four domains, namely Photo (1,670 images), Art Painting (2,048 images), Cartoon (2,344 images) and Sketch (3,929 images). Each domain contains seven categories.

### 2. Model
**Caffenet**
- CaffeNet is a deep learning model architecture, similar to AlexNet but with a simpler structure. It has been widely used for various computer vision tasks, including image classification. CaffeNet typically consists of five convolutional layers followed by three fully connected layers, making it suitable for a range of image-related applications.
- Architecture (reference : [paper](https://www.aimsciences.org/article/doi/10.3934/mfc.2018008))
-![](https://www.researchgate.net/profile/Zhuwei-Qin/publication/325174710/figure/fig1/AS:844228066308096@1578291064136/CaffeNet-architecture.png)


### 3. Milestone
각 step은 3일의 간격을 나타내고 있음
(E: plan, O: done)
|task|1|2|3|4|5|6|7|8|9|10|
|--|--|--|--|--|--|--|--|--|--|--|
|reference 숙지 |E||||||||||
|base 모델 test |E|E|||||||||
|ExampleGen 구현 |E|E|||||||||
|SchemaGen 구현 |E|E|||||||||
|Transform 구현 ||E|E||||||||
|Trainer 구현 ||E|E|E|E||||||
|Evaluator 구현 ||||||E|E||||
|Pusher 구현 |||||||E|E|E||
|repository 정리 ||||E|||||E|E|


    
