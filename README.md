# TimingPredict
This repo contains links to our open source code and dataset for "A Timing Engine Inspired Graph Neural Network Model for Pre-Routing Slack Prediction" (DAC 2022).

**Code**: https://github.com/TimingPredict/TimingPredict

**Dataset**: https://github.com/TimingPredict/Dataset



## About Our Paper

Fast and accurate pre-routing timing prediction is essential for timing-driven placement since repetitive routing and static timing analysis (STA) iterations are expensive and unacceptable. Prior work on timing prediction aims at estimating net delay and slew, lacking the ability to model global timing metrics. In this work, we present a timing engine inspired graph neural network (GNN) to predict arrival time and slack at timing endpoints. We further leverage edge delays as local auxiliary tasks to facilitate model training with increased model performance. Experimental results on real-world open-source designs demonstrate improved model accuracy and explainability when compared with vanilla deep GNN models.

https://dl.acm.org/doi/abs/10.1145/3489517.3530597

```
@inproceedings{mltimerdac22,
 author = {Guo, Zizheng and Liu, Mingjie and Gu, Jiaqi and Zhang, Shuhan and Pan, David Z. and Lin, Yibo},
 booktitle = {Proceedings of the 59th Annual Design Automation Conference 2022},
 organization = {ACM},
 title = {A Timing Engine Inspired Graph Neural Network Model for Pre-Routing Slack Prediction},
 year = {2022}
}
```

