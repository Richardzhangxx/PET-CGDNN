# PET-CGDNN
Source code for the paper "An Efficient Deep Learning Model for Automatic Modulation Recognition Based on Parameter Estimation and Transformation", which is pubulished in IEEE Communications Letters. 

The article is available here：[An Efficient Deep Learning Model for Automatic Modulation Recognition Based on Parameter Estimation and Transformation](https://ieeexplore.ieee.org/abstract/document/9507514)

If you have any question, please contact e-mail: zhangxx8023@gmail.com

# Abstract
Automatic modulation recognition (AMR) is a promising technology for intelligent communication receivers to detect signal modulation schemes. Recently, the emerging
deep learning (DL) research has facilitated high-performance DL-AMR approaches. However, most DL-AMR models only focus on recognition accuracy, leading to huge model sizes and high computational complexity, while some lightweight and low-complexity models struggle to meet the accuracy requirements. This letter proposes an efficient DL-AMR model based on phase parameter estimation and transformation, with convolutional neural network (CNN) and gated recurrent unit (GRU) as the feature extraction layers, which can achieve high recognition accuracy equivalent to the existing state-of-the-art models but reduces more than a third of the volume of their parameters. Meanwhile, our model is more competitive in training time and test time than the benchmark models with similar recognition accuracy. Moreover, we further propose to compress our model by pruning, which maintains the recognition accuracy higher than 90% while has less than 1/8 of the number of parameters comparing with state-of-the-art models.

# Citation
If this paper is helpful to your research, please cite:

    @article{zhang2021efficient,
        title={An Efficient Deep Learning Model for Automatic Modulation Recognition Based on Parameter Estimation and Transformation},
        author={Zhang, Fuxin and Luo, Chunbo and Xu, Jialang and Luo, Yang},
        journal={IEEE Communications Letters},
        year={2021},
        publisher={IEEE}
    }

# Content

【**RML2016.10a**】

<img src="https://user-images.githubusercontent.com/56213845/127735649-520463f2-32ac-4eb7-8884-aaaa0bf7f6f9.png" width="50%">

【**RML2016.10b**】

<img src="https://user-images.githubusercontent.com/56213845/127735650-018c1979-a680-4fb1-ac8c-695b7acef596.png" width="50%">

【**RML2018.01a**】

<img src="https://user-images.githubusercontent.com/56213845/127735652-7ca1b4c3-0c5c-43c4-a3cb-65bf3d5f96b7.png" width="50%">

【**Model comparison on three datasets (A:RML2016.10a, B: RML2016.10b, C: RML2018.01a)**】:
: ![image](https://user-images.githubusercontent.com/56213845/127735733-ed7bddb6-6325-42b1-ab07-9b171023970c.png) :

# Datasets

[RML2016.10a, RML2016.10b, and RML2018.01a](https://www.deepsig.ai/datasets)

# Environment
This model is implemented in Keras, and the environment setting is:
* Python 3.6.10
* TensorFlow-gpu 1.14.0
* Keras-gpu 2.2.4

# Acknowledgement
Thanks [leena201818](https://github.com/leena201818) and [wzjialang](https://github.com/wzjialang/MCLDNN#introduction) for their great work!
