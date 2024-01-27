# Fake Product Review

The project aims on identifying the fake reviews.

# Abstract

In the era of online shopping, the reliability of product reviews plays a crucial role in assisting consumers with informed purchasing decisions. However, the proliferation of fake product reviews poses a significant challenge to the authenticity and trustworthiness of online reviews. This research focuses on the development of a robust machine learning-based system for the detection of fake product reviews. The proposed solution contributes to the ongoing efforts in creating a trustworthy online shopping environment by empowering consumers with reliable information and assisting online platforms in maintaining the integrity of their review systems.
## Objectives
The objective for fake product review detection is to implement a comprehensive and sophisticated system utilizing machine learning algorithms, and user behavior analysis to accurately identify and filter out deceptive reviews. The system aims to analyze only textual content and user profiles for inconsistencies. Continuous learning mechanisms ensure adaptability to evolving fraudulent tactics, while potential collaboration with online platforms and the integration of user authentication mechanisms further enhance the overall effectiveness of the detection system, fostering a more trustworthy and transparent online review ecosystem.

## Proposed System
I have used the Machine Learning Model named Support Vector Machine(**SVM**) which gives more accuracy than other models. In addition to that I have used **oneAPI** which provides betterment of ML models. Support Vector Machines (SVM) is a powerful machine learning technique employed in the realm of fake product review detection. SVM operates by mapping input data into a high-dimensional space and finding the optimal hyperplane that best separates different classes. In the context of detecting fake reviews, SVM analyzes various features extracted from textual content, such as sentiment, word frequency, and linguistic patterns. By training on labeled datasets that distinguish between genuine and deceptive reviews, SVM learns to generalize and classify unseen data effectively. Its ability to handle high-dimensional feature spaces and nonlinear relationships makes SVM particularly suitable for discerning subtle patterns indicative of fraudulent product feedback. This robust approach aids in enhancing the accuracy and reliability of fake review detection systems, contributing to more trustworthy consumer evaluations in the online marketplace.

## Setup

```import pandas as pd```
```pip install scikit-learn```
```pip install gradio```
```from sklearnex import patch_sklearn```
    ```patch_sklearn()```
