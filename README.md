# Hybrid COVID-19 Segmentation and Recognition Framework (HMB-HCF) using Deep Learning and Genetic Algorithms (Research Paper Script)

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/) 
[![GitHub stars](https://img.shields.io/github/stars/HossamBalaha/Hybrid-COVID-19-Segmentation-and-Recognition-Framework-HMB-HCF.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/HossamBalaha/Hybrid-COVID-19-Segmentation-and-Recognition-Framework-HMB-HCF/stargazers/) [![GitHub followers](https://img.shields.io/github/followers/HossamBalaha.svg?style=social&label=Follow&maxAge=2592000)](https://github.com/HossamBalaha?tab=followers) [![GitHub watchers](https://img.shields.io/github/watchers/HossamBalaha/Hybrid-COVID-19-Segmentation-and-Recognition-Framework-HMB-HCF.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/HossamBalaha/Hybrid-COVID-19-Segmentation-and-Recognition-Framework-HMB-HCF/watchers/)

>More information will be written upon the research paper publication.

## (1) Authors:
* **Hossam Magdy Balaha** (Lecturer Assistant at the Computer Engineering and Control Systems Department, Faculty of Engineering, Mansoura University, Egypt, Email: hossam.m.balaha@mans.edu.eg).
* **Magdy Hassan Balaha** (Professor of Obstetrics and Gynecology, Faculty of Medicine, Tanta University, Egypt, Email: magdy.balaha@med.tanta.edu.eg).
* **Hesham Arafat Ali** (Professor at the Computer Engineering and Control Systems Department, Faculty of Engineering, Mansoura University, Egypt, Email: h_arafat_ali@mans.edu.eg).

## (2) Abstract:
COVID-19 (Coronavirus) went through a rapid escalation until it became a pandemic disease. The normal and manual medical infection discovery may take few days and therefore computer science engineers can share in the development of the automatic diagnosis for fast detection of that disease. The study suggests a hybrid COVID-19 framework (named HMB-HCF) based on deep learning (DL), genetic algorithm (GA), weighted sum (WS), and majority voting principles in nine phases. Its segmentation phase suggests a lung segmentation algorithm using X-Ray images (named HMB-LSAXI) for extracting lungs. Its classification phase is built from a hybrid convolutional neural network (CNN) architecture using an abstractly-designed CNN (named HMB1-COVID19) and transfer learning (TL) pre-trained models (VGG16, VGG19, ResNet50, ResNet101, Xception, DenseNet121, DenseNet169, MobileNet, and MobileNetV2). The hybrid CNN architecture is used for learning, classification, and parameters optimization while GA is used to optimize the hyperparameters. This hybrid working mechanism is combined in an overall algorithm named HMB-DLGA. The study experiments implemented the WS approach to evaluate the models' performance using the loss, accuracy, F1-score, precision, recall, and area under curve (AUC) metrics with different pre-defined ratios. A collected, combined, and unified X-Ray dataset from 8 different public datasets was used alongside the regularization, dropout, and data augmentation techniques to limit the overall overfitting. The applied experiments reported state-of-the-art metrics. VGG16 reported 100% WS metric (i.e., 0.0097, 99.78%, 0.9984, 99.89%, 99.78%, and 0.9996 for the loss, accuracy, F1, precision, recall, and AUC respectively) concerning the highest WS. It also reported a 99.92% WS metric (i.e., 0.0099, 99.84%, 0.9984, 99.84%, 99.84%, and 0.9996 for the loss, accuracy, F1, precision, recall, and AUC respectively) concerning the last reported WS result. HMB-HCF was validated on 13 different public datasets to verify its generalization. The best-achieved metrics were compared with 13 related studies. These extensive experiments' target was the applicability verification and generalization.

## (3) Keywords:
* Classification.
* Convolutional Neural Network (CNN).
* COVID-19.
* Data Augmentation (DA).
* Deep Learning (DL).
* Genetic Algorithms (GA).
* Optimization.
* Transfer Learning (TL).

## (4) Paper Information:
* DOI: https://doi.org/10.1016/j.artmed.2021.102156
* Link: https://www.sciencedirect.com/science/article/pii/S0933365721001494?dgcid=author#!

## (5) Citation:
Cite this as:
>Balaha, H. M., Balaha, M. H., & Ali, H. A. (2021). Hybrid COVID-19 segmentation and recognition framework (HMB-HCF) using deep learning and genetic algorithms. Artificial Intelligence in Medicine, 102156.‏
```
@article{balaha2021hybrid,
  title={Hybrid COVID-19 segmentation and recognition framework (HMB-HCF) using deep learning and genetic algorithms},
  author={Balaha, Hossam Magdy and Balaha, Magdy Hassan and Ali, Hesham Arafat},
  journal={Artificial Intelligence in Medicine},
  pages={102156},
  year={2021},
  publisher={Elsevier}
}
```

## (6) Licence:
[![licensebuttons by-nc-sa](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0)

The **Hybrid COVID-19 Segmentation and Recognition Framework (HMB-HCF) using Deep Learning and Genetic Algorithms** script is licensed by **CC BY-NC-SA 4.0**.

>The **CC BY-NC-SA 4.0** is one of the Creative Commons (CC) licenses and allows the different users to share the script only if they (1) give the credits to the copyright holders, (2) do not use the script for any commercial purposes, and (3) distribute any additions, transformations or changes to the script under this same license.

Full Description: https://creativecommons.org/licenses/by-nc-sa/4.0/

## (7) More Information About Me:
Online CV: https://hossambalaha.github.io/