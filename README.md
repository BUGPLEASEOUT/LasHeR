# A Large-scale High-diversity Benchmark for RGBT Tracking

RGBT tracking receives a surge of interest in the computer vision community, but this research field lacks a large-scale and high diversity benchmark dataset, which is essential for both the training of deep RGBT trackers and the comprehensive evaluation of RGBT tracking methods. To this end, we present a **La**rge-**s**cale **H**igh-diversity b**e**nchmark for **R**GBT tracking (**LasHeR**) in this work.

![image](https://github.com/BUGPLEASEOUT/LasHeR/blob/main/figure0/LasHeR_paris.PNG)

## About LasHeR benchmark

* **Large-scale**
* **Multi-platform imaging devices**
* **Rich scenes and categories**
* **Real-world challenges**
![](https://github.com/BUGPLEASEOUT/LasHeR/blob/main/figure0/Comparison_Bub.PNG)

LasHeR consists of **1224** visible and thermal infrared video pairs with **more than 730K** frame pairs in total. Each frame pair is spatially aligned and manually annotated with a bounding box, making the dataset well and densely annotated.
LasHeR is highly diverse capturing from a broad range of *object categories*, *camera viewpoints*, *scene complexities* and *environmental factors* across seasons, weathers, day and night. Induced by real-world applications, several *new challenges* are take into consideration in data creation. 

### Comparison of LasHeR with public RGBT datasets
![](https://github.com/BUGPLEASEOUT/LasHeR/blob/main/figure0/Comparision_Tab.PNG)

### Dataset file structure
-sequence  
--visible  
---v000.jpg  
---v001.jpg   
--infrared  
---i000.jpg  
---i001.jpg   
--init.txt  
--visible.txt  
--infrared.txt  

## Evaluation on LasHeR
We evaluate 12 RGBT tracking algorithms on LasHeR to provide comprehensive platform of performance analysis. Deep RGBT trackers include MANet, DAPNet, MaCNet, DAFNet, FANet, MANet++ , DMCNet and mfDiMP. RGBT trackers based on handcrafted features include SGT, CMR and SGT++.
![](https://github.com/BUGPLEASEOUT/LasHeR/blob/main/figure0/evaluation.PNG)

## Dataset
* Download LasHeR from [here]().
