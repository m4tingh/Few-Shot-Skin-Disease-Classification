# ISIC skin disease image dataset labelled

25,331 images.
This dataset is to facilitate image classification for 8 skin diseases:
1.	Actinic keratosis (867)
2.	Basal cell carcinoma (3323)
3.	Benign keratosis (2624)
4.	Dermatofibroma (239)
5.	Melanocytic nevus (12875)
6.	Melanoma (4522)
7.	Squamous cell carcinoma (628)
8.	Vascular lesion (253)

**Why This Dataset?**
The ISIC-labelled skin disease image dataset provides a highly suitable benchmark for few-shot learning experiments in the medical domain. It contains images from 8 different skin disease classes, with a highly imbalanced distribution of samples — ranging from over 12,000 examples in the "Melanocytic nevus" class to fewer than 300 in classes like "Dermatofibroma" or "Vascular lesion".

This inherent imbalance realistically reflects real-world medical challenges, where certain conditions are much rarer than others. Such a setup naturally creates a low-data scenario for several classes, making it ideal for evaluating the performance of meta-learning models like **Prototypical Networks**, which are designed to generalize well with only a few labeled examples.

Furthermore, the dataset’s folder-based structure (one folder per class) is perfectly aligned with the episodic training setup required for few-shot classification tasks. It supports flexible N-way K-shot configurations (e.g., 5-way 1-shot, 3-way 5-shot, etc.), allowing for extensive experimentation.
In addition, the dataset is derived from the well-known **ISIC (International Skin Imaging Collaboration)** repository, a globally recognized source for dermatological image data. This adds credibility and relevance to our experiments, particularly in healthcare-related machine learning research.

In summary, the combination of real-world class imbalance, medical importance, data structure, and trusted source makes this dataset a strong candidate for exploring meta-learning in few-shot image classification.




Link:
https://www.kaggle.com/datasets/riyaelizashaju/isic-skin-disease-image-dataset-labelled/data
