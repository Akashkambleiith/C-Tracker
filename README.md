Currently available Multiple-Object Tracking (MOT)
systems either follow the tracking-by-detection paradigm,
in which object detection, feature extraction, and data association are all performed separately, or combine two of
the three phases.In this paper, the authors proposed an end-to-end online MOT model, that takes two adjacent frames as its input,
combining the object detection, feature representation, and
data association into a simple paired bounding boxes regression problem. A joint attention module is introduced to
highlight informative regions for the paired bounding boxes
regression. State-of-the-art performances have been obtained on the most widely used public benchmark datasets.

Submitted by following as part of AI5100 course: 
- Rishabh Bhardwaj
- Lakshmi Gayathri Gudipudi
- Shridharam Tiwari
- Akash Kamble
- Gaurav Kumar


```BibTeX
@inproceedings{peng2020ctracker,
  title={Chained-Tracker: Chaining Paired Attentive Regression Results for End-to-End Joint Multiple-Object Detection and Tracking},
  author={Peng, Jinlong and Wang, Changan and Wan, Fangbin and Wu, Yang and Wang, Yabiao and Tai, Ying and Wang, Chengjie and Li, Jilin and Huang, Feiyue and Fu, Yanwei},
  booktitle={Proceedings of the European Conference on Computer Vision},
  year={2020},
}
```
