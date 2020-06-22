# AI for Medical Diagnosis

## Key Concepts by Week

### Week 1, Disease detection with computer vision

> By the end of this week, you will practice classifying diseases on chest x-rays using a neural network....

- Data pre-processing: checking for data leakage
- Preprocess images properly for the train, validation and test sets
- Implement a weighted loss function to address class imbalance.
- Set up a pre-trained neural network to make disease predictions on chest x-rays.

**Papers**

- [Dermatologist-level classification of skin cancer with deep neural networks](https://www.nature.com/articles/nature21056)
- [Fundus photograph-based deep learning algorithms in detecting diabetic retinopathy](https://www.nature.com/articles/s41433-018-0269-y)
- [Impact of Deep Learning Assistance on the Histopathologic Review of Lymph Nodes for Metastatic Breast Cancer](https://pubmed.ncbi.nlm.nih.gov/30312179/)

**Key Points**

Model Training
![](https://i.imgur.com/CN0OQsu.png)

Model Testing
![](https://i.imgur.com/Bn9IPXW.png)


### Week 2, Evaluating models

> By the end of this week, you will practice implementing standard evaluation metrics to see how well a model performs in diagnosing diseases....

- Calculate true positives, true negatives, false positives, false negatives.
- Calculate sensitivity and specificity
- Calculate Positive Predictive Value (PPV) and Negative Predictive Value (NPV).
- Understand confidence intervals, ROC curve, and F1 score.

### Week 3, Image segmentation on MRI images

> By the end of this week, you will prepare 3D MRI data, implement an appropriate loss function for image segmentation, and apply a pre-trained U-net model to segment tumor regions in 3D brain MRI images....

- Perform image segmentation on 3D MRI data.
- Take random sub-samples from a 3D image.
- Standardize an input image.
- Apply a pre-trained U-Net model.
- Implement a proper loss function for model training (soft dice loss).
- Evaluate model performance by calculating sensitivity and specificity.