Dense Feature Weighted Fusion Network for Insulator Surface Defect Detection Under Complex Weather Conditions
=
1.Abstract
----
In the inspection of power transmission system, due to the influence of various complex weather, the imaging of insulator can easily be obscured and blurred. Aiming at this problem, in order to better reflect the real patrol scenes, the study firstly constructs a comprehensive data set using Albumentations image enhancement framework, including images of insulators under various complex meteorological conditions, such as normal weather, solar radiation, rain, fog, snow and so on. Secondly, based on the YOLOv5s model, two deep dense feature-weighted fusion neck networks are proposed to replace the original neck networks, in order to strengthen the ability to learn weak and vague features in various complex weather. Finally, Focal-Efficient IOU Loss is introduced as the loss function in the head network of the model to deal with the problem of positive and negative sample unbalance of boundary box regression due to complex weather interference. Experiments show that when the IOU threshold is 0.5, the mean average accuracy of the proposed model in complex weather insulator data sets reaches 99.3%, and the detection precision and recall rate reach 100% and 98.1%, respectively. Compared with other detection models, the model shows good performance in all evaluation indexes, and successfully realizes high-precision detection of surface defects of insulators in complex weather.  <br>  <br>
2.Improved Network Architecture
----
![DenseNet](https://github.com/2462954048/Dense-Feature-Weighted-Fusion-Network-for-Insulator-Detection-Under-Complex-Weather-Conditions/assets/45593319/43d767bf-22da-4a7c-8606-3141808fd8bd)<br>  <br>
We have published the network for the proposed doubleNeck and denseNeck, which can be accessed at : YOLOv5-DenseNeck.yaml,YOLOv5-DoubleNeck.yaml.  <br>  <br>
3.Implementation
----
The proposed architecture is implemented using the PyTorch framework (1.8.1+cu111) with a single GeForce RTX 3090 GPU of 24 GB memory.  <br>  <br>
3.1 Dataset
-----
We have published the code of Complex-Weather-Insulator-Dataset, which can be accessed at the link: (https://pan.baidu.com/s/1Qt-5PJnCnLOTHRbie1-3_Q ), and the download code: 0000.  <br>  <br>
We have published the code of Complex-Weather-Insulator-Dataset enhancement based on the albumentations framework, which can be accessed at MyAlbumentationEnhance-inlustator.py. <br>  <br>

4.License
----
The source code is free for research and education use only. Any comercial use should get formal permission first.  <br>  <br>
5.Contact
----
Please contact 2021203258@cqust.edu.cn for any further questions.



