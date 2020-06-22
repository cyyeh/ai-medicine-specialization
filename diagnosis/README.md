# AI for Medical Diagnosis

## Week 1, Disease detection with computer vision

> By the end of this week, you will practice classifying diseases on chest x-rays using a neural network....

- Data pre-processing: checking for data leakage
- Preprocess images properly for the train, validation and test sets
- Implement a weighted loss function to address class imbalance.
- Set up a pre-trained neural network to make disease predictions on chest x-rays.

### Key Points

**Model Training**
![](https://i.imgur.com/CN0OQsu.png)

**Model Testing**
![](https://i.imgur.com/Bn9IPXW.png)

### Papers

- [Dermatologist-level classification of skin cancer with deep neural networks](https://www.nature.com/articles/nature21056)
- [Fundus photograph-based deep learning algorithms in detecting diabetic retinopathy](https://www.nature.com/articles/s41433-018-0269-y)
- [Impact of Deep Learning Assistance on the Histopathologic Review of Lymph Nodes for Metastatic Breast Cancer](https://pubmed.ncbi.nlm.nih.gov/30312179/)
- [CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning](https://arxiv.org/pdf/1711.05225.pdf)
- [CheXpert: A Large Chest Radiograph Dataset
with Uncertainty Labels and Expert Comparison](https://arxiv.org/pdf/1901.07031.pdf)
- [Deep learning for chest radiograph diagnosis: A retrospective comparison of the CheXNeXt algorithm to practicing radiologists](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002686)

### Quiz

<details>
  <summary>Answers</summary>
  
  ![](https://i.imgur.com/m6lKM3P.png)
  ![](https://i.imgur.com/01Tlpi9.png)
  ![](https://i.imgur.com/7no4M1K.png)
  ![](https://i.imgur.com/iNN3S3t.png)
  ![](https://i.imgur.com/PZuvOI0.png)
  ![](https://i.imgur.com/08wdHXJ.png)
  ![](https://i.imgur.com/cjzIxww.png)
  ![](https://i.imgur.com/AC7XYPt.png)
  ![](https://i.imgur.com/4qRFCRS.png)
  ![](https://i.imgur.com/XCB7rEK.png)
  ![](https://i.imgur.com/XCAQFXB.png)
</details>


### Project

- [Chest X-Ray Medical Diagnosis with Deep Learning](https://github.com/cyyeh/ai-medicine-specialization/blob/master/diagnosis/project/Chest%20X-Ray%20Medical%20Diagnosis.ipynb)

## Week 2, Evaluating models

> By the end of this week, you will practice implementing standard evaluation metrics to see how well a model performs in diagnosing diseases....

- Calculate true positives, true negatives, false positives, false negatives.
- Calculate sensitivity and specificity
- Calculate Positive Predictive Value (PPV) and Negative Predictive Value (NPV).
- Understand confidence intervals, ROC curve, and F1 score.

### Key Points

**Accuracy**
![](https://i.imgur.com/O6pndP6.png)

**PPV, NPV, Sensitivity, Specificity**
![](https://i.imgur.com/kRUqrHI.png)

**Confusion Matrix**
![](https://i.imgur.com/Y3nDb1A.png)

![](https://i.imgur.com/vptQoue.png)

**Confidence Interval**
![](https://i.imgur.com/jBjcKPu.png)

![](https://i.imgur.com/pE54OKq.png)

![](https://i.imgur.com/3uQZipw.png)

### Quiz

<details>
  <summary>Answers</summary>
  
  ![](https://i.imgur.com/kyFiK9L.png)
  ![](https://i.imgur.com/BkbIiHm.png)
  ![](https://i.imgur.com/nK0gRcN.png)
  ![](https://i.imgur.com/bf54OB2.png)
  ![](https://i.imgur.com/VUASkJc.png)
  ![](https://i.imgur.com/NjhIKvB.png)
  ![](https://i.imgur.com/u6KPumg.png)
  ![](https://i.imgur.com/VS7mVNN.png)
  ![](https://i.imgur.com/Nvm0z77.png)
  ![](https://i.imgur.com/9iTpKac.png)
  ![](https://i.imgur.com/qZ1HOIb.png)
</details>

## Week 3, Image segmentation on MRI images

> By the end of this week, you will prepare 3D MRI data, implement an appropriate loss function for image segmentation, and apply a pre-trained U-net model to segment tumor regions in 3D brain MRI images....

- Perform image segmentation on 3D MRI data.
- Take random sub-samples from a 3D image.
- Standardize an input image.
- Apply a pre-trained U-Net model.
- Implement a proper loss function for model training (soft dice loss).
- Evaluate model performance by calculating sensitivity and specificity.