# DMHA
The dataset and code for Connecting the Complementary-view Videos: Joint Camera Identification and Subject Association in CVPR 2022, which we also called as Deep Multi-Human Association (DMHA).

## Introduction

<div align= justify>

We attempt to connect the data from complementary views, i.e., top view from drone-mounted cameras in the air, and side view from wearable cameras on the ground, as shown in the below figure.
Collaborative analysis of such complementary-view data can facilitate to build the air-ground cooperative visual system for various kinds of applications. 
This is a very challenging problem due to the large view difference between top and side views. 

<div align=center><img src="https://github.com/RuizeHan/DMHA/blob/main/figs/example.jpg" width="825" height="125" alt="example"/><br/>

&emsp;
  
<div align= justify>
  
In this work, we develop a new approach that can simultaneously handle three tasks: i) localize the side-view camera in the top view; ii) estimate the view direction of the side-view camera; iii) detect and associate the same subjects on the ground across the complementary views. Our main idea is to explore the spatial position layout of the subjects in two views. In particular, we propose a spatial-aware position representation method to embed the spatial-position distribution of the subjects in different views. We further design a cross-view video collaboration framework composed of a camera identification module and a subject association module to simultaneously perform the above three tasks. We collect a new synthetic dataset consisting of top-view and side-view video sequence pairs for performance evaluation.

### Dataset (Synthetic):

Link (Baidu Drive)：https://pan.baidu.com/s/1u_ed8w4cTe_w9bz1_Sk2ZA 
Password：DMHA

### Code:
We have released the source code submitted to CVPR-22 as the supplementary material. 
<!-- We plan to provide the clean code with more detailed informations before the main conference of CVPR 2022. --> 

### Cite
```
@inproceedings{han2022dmha,
  title={Connecting the Complementary-view Videos: Joint Camera Identification and Subject Association}, 
  author={Han, Ruize and Gan, Yiyang and Li, Jiacheng and Wang, Feifan and Feng, Wei and Wang, Song},  
  year={2022},  
  booktitle={IEEE/CVF Conference on Computer Vision and Pattern Recognition}
}
  ```
