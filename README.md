# 🧬 hubmap-tf-kaggle

This repository contains our Kaggle submission for the **HuBMAP + HPA - Hacking the Human Body** competition.

---



## Project Summary

-  **Task:** Semantic segmentation of Functional Tissue Units (FTUs) versus background in biopsy slides from multiple human organs.

-  **Model:** UNet architecture with EfficientNet-B8 as encoder; decoder integrates Feature Pyramid Network (FPN) and Atrous Spatial Pyramid Pooling (ASPP).

-  **Evaluation Metric:** Dice Similarity Coefficient (DSC)



## Development Environment

-  **TensorFlow version:** 2.4.1  
-  **TensorFlow Keras version:** 2.4.0  
-  **Python version:** 3.7.10  
-  **GCC version:** 9.3.0  

 **Kaggle datasets used:**  
- `efficientnetv2-head-1x1-endpoint-v2`  
- `hubmap-patched-tfrecords-300x300`



## How to Run

This project was originally developed and tested on **Kaggle**.  
Notebooks and dependencies are designed to be compatible with Kaggle's hosted GPU/TPU environments.



## Publication

 **Segmentation of Multi-Organ Functional Tissue Units Using UNet-EfficientNet-B8**  (https://dl.acm.org/doi/10.1145/3644116.3644158)

