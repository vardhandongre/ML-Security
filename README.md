# ML-Security

A video can be thought of simply as a sequence of images. That is, a network designed for learning from videos should be able to handle the spatial information as well as the temporal information. 

Key points:
- Primary Dataset: Facebook DFDC
- Resnet model with 3D CNN
- Pre-trained on Kinetics dataset
- Fine tuned upper layers on DFDC dataset
- Data Augmented using: Random Cropping, Random Flipping, Brightness Adjustment
- Baselines: MesoNet: Detecting Facial Forgeries, Face Warping Artifacts Identification


References:
1. Human-Action Recognition work 
2. Learning Spatiotemporal Features with 3D Convolutional Networks Tran et. al (2015)
3. Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet? Hara et. al (2017) 

