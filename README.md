# COBRA: Contrastive Bi-Modal Representation Algorithm

This repository contains the code for the paper COBRA: Contrastive Bi-Modal Representation Algorithm by [Vishaal Udandarao](https://vishaal27.github.io/), [Abhishek Maiti](http://ovshake.me), Deepak Srivatsav, Suryatej Reddy, Yifang Yin and [Rajiv Ratn Shah](http://faculty.iiitd.ac.in/~rajivratn/). 

## Methodology 
We present a novel framework COBRA that aims to train two modalities (image and text) in a joint fashion inspired by the **Contrastive Predictive Coding (CPC)** and **Noise Contrastive Estimation (NCE)** paradigms which preserve both inter and intra-class relationships. We empirically show that this framework reducesthe modality gap significantly and generates a robust and task agnostic joint-embedding space. We outperform existing work on four diverse downstream tasks spanning across seven benchmark cross-modal datasets.<br>

**A visualisation of the loss function**:
<br>
<br>
![Supervised Contrastive Loss](https://github.com/ovshake/cobra/blob/master/images/CPCLoss.JPG)



## Architecture

![](https://github.com/ovshake/cobra/blob/master/images/Architecture.JPG)


## Datasets
The 7 datasets used to empirically prove our results are:<br> 
1. PKU-XMedia 
2. MS-COCO 
3. NUS-Wide 10k 
4. Wikipedia
5. FakeNewsNet
6. MeTooMA
7. CrisisMMD

## Results

![Wikipedia](https://github.com/ovshake/cobra/blob/master/images/Wiki.JPG)
![MS-COCO](https://github.com/ovshake/cobra/blob/master/images/MSCoco.JPG)
![PKU-XMedia](https://github.com/ovshake/cobra/blob/master/images/PKU-XMedia.JPG)
![MS-COCO](https://github.com/ovshake/cobra/blob/master/images/NUS-Wide.JPG)
![MS-COCO](https://github.com/ovshake/cobra/blob/master/images/FakeNewsNet.JPG)
![MS-COCO](https://github.com/ovshake/cobra/blob/master/images/MeTooMA.JPG)
![MS-COCO](https://github.com/ovshake/cobra/blob/master/images/CrisisMMD.JPG)


## Instructions for running

## Queries
In case of any queries, please open an issue. We will respond as soon as possible. 
