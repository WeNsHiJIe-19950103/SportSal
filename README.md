# SportSal

## This repository provides the dataset and code for reproducing the results in the paper: SportSal: Hypernetwork-based Saliency Prediction for Sports Videos

Predicting video saliency is crucial for improving sports video processing efficiency, thereby providing an enriched viewing experience for a wide-ranging audience. However, there is a long-term absence of well-established eye-tracking dataset and learning-based approach, particularly tailored for sports videos. In this paper, we establish a large-scale eye-tracking dataset dubbed audio-visual sports (AVS). AVS consists of 1,000 high-quality sports videos with eye fixations from 60 participants.  Through data analysis on AVS, we observe that human attention patterns exhibit significant variations based on the specific scene context of the sports. Motivated by our observations, we propose a sports-aware saliency prediction  approach, named SportSal, which can adaptively predict saliency maps in a hyper manner. Specifically, a hypernetwork is introduced to learn sports-aware priors. Meanwhile, an audio-visual fusion (AVF) block is developed to effectively fuse features from the visual and audio backbone. Given the learned priors and fused audio-visual features, we propose the hyper deformable convolutional (HDC) block and the hyper upsampling (HU) block for dynamic feature extraction and upsampling, respectively. The two blocks are sequentially connected to adaptively predict saliency maps. Experimental results show that our approach outperforms 16 state-of-the-art saliency prediction models over three sports video eye-tracking datasets. Finally, we demonstrate the application of our SportSal approach in perceptual video compression. 


![framework](https://github.com/user-attachments/assets/95356ecf-d79f-47d7-b224-2a14e1c8cf3e)

#### For downloading the AVS dataset, please refer to the conference version of this work. [AVS dataset](https://github.com/MinglangQiao/Sports_saliency)
