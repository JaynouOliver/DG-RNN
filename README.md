# DG-RNN

This repository contains the official PyTorch implementation of the following paper:


> **Domain Knowledge Guided Deep Learning with Electronic Health Records (ICDM2019)**<br>
> Changchang yin, Rongjian Zhao, Buyue Qian, Xin Lv, Ping Zhang<br>
> [paper](https://ieeexplore.ieee.org/document/8970777)
>
> **Abstract:** *Due to their promising performance in clinical risk prediction with Electronic Health Records (EHRs), deep learning methods have attracted significant interest from healthcare researchers. However, there are 4 challenges: (i) Data insufficiency. Many methods require large amounts of training data to achieve satisfactory results. (ii) Interpretability. Results from many methods are hard to explain to clinicians (e.g., why the models make particular predictions and which events cause clinical outcomes). (iii) Domain knowledge integration. No existing method dynamically exploits complicated medical knowledge (e.g., relations such as cause and is-caused-by between clinical events). (iv) Time interval information. Most existing methods only consider the relative order of visits from EHRs, but ignore the irregular time intervals between neighboring visits. In the study, we propose a new model, Domain Knowledge Guided Recurrent Neural Networks (DG-RNN), by directly introducing domain knowledge from the medical knowledge graph into an RNN architecture, as well as taking the irregular time intervals into account. Experimental results on heart failure risk prediction tasks show that our model not only outperforms state-of-the-art deep-learning based risk prediction models, but also associates individual medical events with heart failure onset, thus paving the way for interpretable accurate clinical risk predictions.  *

# Environment
Ubuntu16.04, python2.7
```
pip install -r requirement.txt
```



# Data preparing 
-	Replace the folder data with your own data.

# Model Training
```
cd code
python main.py
```

