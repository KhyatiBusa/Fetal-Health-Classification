# Fetal-Health-Classification
This project analyzes CTG data to classify fetal health as "Normal" or "At Risk," identifying key factors like heart rate variability. The goal is to support early interventions and reduce child mortality, though limitations include dataset scope and loss of detail from simplifying the classification.

Introduction

Fetal mortality is a major, but often overlooked, public health problem. With fetal mortality comes greater risk of adverse maternal health outcomes, as well as maternal mortality risk increase. Cardiotocograms (CTGs) measure values such as fetal heart rate, fetal movement, and uterine contractions. CTGs are a simple and cost-accessible option to assess fetal health, allowing healthcare professionals to take action in order to prevent child and maternal mortality.

Business Problem

The main business problem is to assess the health status of fetuses during pregnancy using CTG data. While this is arguably more of a health problem than a business problem, by accurately classifying fetal health as "Normal" or "At Risk," healthcare professionals can proactively identify cases that require closer monitoring and timely intervention. Early detection of potential complications can help prevent adverse outcomes for both the fetus and the mother.

Data Understanding

"Reduction of child mortality is reflected in several of the United Nations' Sustainable Development Goals and is a key indicator of human progress. The UN expects that by 2030, countries end preventable deaths of newborns and children under 5 years of age, with all countries aiming to reduce under‑5 mortality to at least as low as 25 per 1,000 live births. As mentioned above Cardiotocograms (CTGs) are a cost accessible and simple option, the equipment itself works by sending ultrasound pulses and reading its response, thus shedding light on fetal heart rate (FHR), fetal movements, uterine contractions and more.
The dataset used for this project can be found at https://www.kaggle.com/andrewmvd/fetal-health-classification. It contains 2,126 rows of 22 features extracted from Cardiotocogram (CTG) exams, which were then classified by three expert obstetricians into 3 classes:

•	Normal
•	Suspect
•	Pathological

Analysis and Results 

I imported data from reputable sources, then cleaned, processed, scaled, and adjusted the data to account for class imbalance. I utilized descriptive statistics as well as visualizations to illuminate trends in the data and isolate key factors for making fetal health predictions. 
The original data had three possible fetal health outcomes: Normal, Suspect, and Pathological.
<img src="https://github.com/user-attachments/assets/24fab023-208a-4f6d-8712-932e679037a5" alt="image" width="400/">

I combined the Suspect and Pathological classes into a category called At Risk to transform this into a binary classification problem.
 
There is a correlation between prolonged fetal heart rate deceleration and fetal health outcome. Generally speaking, the greater number of prolonged decelerations, the greater the risk. 
 
There was a clear relationship between abnormal short and long term fetal heart rate variability and fetal health outcome.
 


Conclusion
In conclusion, this data analysis project focused on fetal health classification using Cardiotocogram (CTG) exam data, aiming to contribute to the reduction of child mortality and maternal health risks. The findings from this analysis provide valuable information for healthcare professionals and decision-makers to take appropriate actions in the context of fetal health. The identification of key factors that influence fetal health predictions can aid in the timely intervention and prevention of adverse outcomes, ultimately contributing to the UN's Sustainable Development Goals of reducing child mortality and improving maternal health.

Limitations
However, it is crucial to acknowledge the limitations of this analysis. The dataset may not encompass all possible factors influencing fetal health, and further research and data collection might be needed to enhance the model's accuracy and generalizability. Additionally, the binary classification approach might overlook valuable insights present in the original three-class problem, and its impact on model performance should be considered.
