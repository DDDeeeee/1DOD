# 1DOD

### One-Dimensional Object Detection for Streaming Text Segmentation of Meeting Dialogue (ACL 2025 Findings)
------

## 🔬 1D Object Detection
Example of 1D object detection. We used a single-edged version:  
<img src="https://github.com/DDDeeeee/1DOD/blob/main/pics/1.png" alt="Example of 1D object detection. We used a single-edged version." style="zoom:12%;" />

## 🛸 Task Process
Traditional classification task combined with 1D bounding-box regression task:  
<img src="https://github.com/DDDeeeee/1DOD/blob/main/pics/2.png" alt="Traditional classification task combined with 1D bounding-box regression task." style="zoom:60%;" />

## 💖 Acknowledgments
This paper is mainly based on the following works:  
- [Alimeeting4mug](https://github.com/alibaba-damo-academy/SpokenNLP/tree/main/alimeeting4mug)(ICASSP2023)  
- [PoNet](https://github.com/lxchtan/ponet)(ICLR2022)  
- [SeqModel](https://arxiv.org/abs/2107.09278)(ASRU 2021)  

## ✒️ Citation
```
@inproceedings{he-etal-2025-one,
    title = "One-Dimensional Object Detection for Streaming Text Segmentation of Meeting Dialogue",
    author = "He, Rui  and
      Wang, Zhongqing  and
      Qiang, Minjie  and
      Wang, Hongling  and
      Yifan.zhang, Yifan.zhang  and
      Xu, Hua  and
      Fan, Shuai  and
      Zhou, Guodong",
    editor = "Che, Wanxiang  and
      Nabende, Joyce  and
      Shutova, Ekaterina  and
      Pilehvar, Mohammad Taher",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2025",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-acl.213/",
    pages = "4118--4130",
    ISBN = "979-8-89176-256-5",
    abstract = "Dialogue text segmentation aims to partition dialogue content into consecutive paragraphs based on themes or logic, enhancing its comprehensibility and manageability. Current text segmentation models, when applied directly to STS (Streaming Text Segmentation), exhibit numerous limitations, such as imbalances in labels that affect the stability of model training, and discrepancies between the model{'}s training tasks (sentence classification) and the actual text segmentation that limit the model{'}s segmentation capabilities.To address these challenges, we first implement STS for the first time using a sliding window-based segmentation method. Secondly, we employ two different levels of sliding window-based balanced label strategies to stabilize the training process of the streaming segmentation model and enhance training convergence speed. Finally, by adding a one-dimensional bounding-box regression task for text sequences within the window, we restructure the training approach of STS tasks, shifting from sentence classification to sequence segmentation, thereby aligning the training objectives with the task objectives, which further enhanced the model{'}s performance. Extensive experimental results demonstrate that our method is robust, controllable, and achieves state-of-the-art performance."
}
```
