# PET-CGDNN
Source code for the paper "An Efficient Deep Learning Model for Automatic Modulation Recognition Based on Parameter Estimation and Transformation", which is implemented in Keras.
This code will be released as soon as the paper is accepted.

【**Abstract**】
Automatic modulation recognition (AMR) is a promising technology for intelligent communication receivers to detect signal modulation schemes. Recently, the emerging
deep learning (DL) research has facilitated high-performance DL-AMR approaches. However, most DL-AMR models only focus on recognition accuracy, leading to huge model sizes and high computational complexity, while some lightweight and low-complexity models struggle to meet the accuracy requirements. This letter proposes an efficient DL-AMR model based on phase parameter estimation and transformation, with convolutional neural network (CNN) and gated recurrent unit (GRU) as the feature extraction layers, which can achieve high recognition accuracy equivalent to the existing state-of-the-art models but reduces more than a third of the volume of their parameters. Meanwhile, our model is more competitive in training time and test time than the benchmark models with similar recognition accuracy. Moreover, we further propose to compress our model by pruning, which maintains the recognition accuracy higher than 90% while has less than 1/8 of the number of parameters comparing with state-of-the-art models.

【**RML2016.10a**】:
![2016A](https://user-images.githubusercontent.com/56213845/127735649-520463f2-32ac-4eb7-8884-aaaa0bf7f6f9.png)
【**RML2016.10**b】:
![2016B](https://user-images.githubusercontent.com/56213845/127735650-018c1979-a680-4fb1-ac8c-695b7acef596.png)
【**RML2018.01a**】：
![2018](https://user-images.githubusercontent.com/56213845/127735652-7ca1b4c3-0c5c-43c4-a3cb-65bf3d5f96b7.png)

【**Model comparison on three datasets (A:RML2016.10a, B: RML2016.10b, C: RML2018.01a)**】:
![image](https://user-images.githubusercontent.com/56213845/127735733-ed7bddb6-6325-42b1-ab07-9b171023970c.png)



