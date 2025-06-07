# Few-Shot Classification of Skin Disease Images Using Prototypical Networks (Meta-Learning)

**(This project is still in progress)**

## Introduction
In recent years, the use of machine learning and deep learning in the healthcare domain has expanded significantly. Among various applications, the analysis and classification of medical images play a crucial role in enabling faster and more accurate diagnosis. Despite notable advances, one of the key challenges in practical adoption of these technologies in medicine is the lack of labeled data. This issue arises due to various reasons such as patient privacy concerns, high costs of data collection and annotation, and the need for expert knowledge to produce high-quality datasets.

This challenge is particularly evident in dermatology, where skin disease images are generally scarce and highly imbalanced across classes. In such scenarios, traditional deep learning models, which require large volumes of data for training, often face performance limitations and fail to generalize effectively.



## Problem Statement
*The aim of this project is to explore and implement an effective and modern approach based on meta-learning for classifying skin disease images in low-data settings. Specifically, we seek to answer this question:*
**How can we accurately classify skin disease images using only a few available examples per class?**
To address this problem, we employ the Prototypical Networks model — a method well-suited for few-shot learning scenarios due to its simplicity, fast convergence, and strong ability to adapt to limited data. This model generates a prototype (representative vector) for each class and classifies new samples based on their distance from these prototypes.
In this research, we evaluate the accuracy and performance of the model using the standardized ISIC skin disease image dataset, and analyze the results in practical, real-world conditions.

