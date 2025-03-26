# Kaggle Project: VIR_WiDS_Team-Ganglia

### **👥 Team Members**

| Name | GitHub Handle | Contribution |
| ----- | ----- | ----- |
| Dineshman Bajracharya | @? | Fill in |
| Grace Yang | @gy180 | fill in |
| Sunny Sun | @ss303 | fill in |
| Sadia Sharmin | @ssharmin28 | Handled null data and model testing. Made improvements, such as parameter testing and implementing ensemble methods, to the model to increase accuracy. |

---

## **🎯 Project Highlights**

**Example:**

* Built a Random Forest Model using multiclass Ridge Classifier, Random Forest, and Stacking Classifier to solve WiDS Datathon 2025 about predicting sex and ADHD diagnoses.
* Achieved an F1 score of \[insert score\] and a ranking of \[insert ranking out of participating teams\] on the final Kaggle Leaderboard
* Implemented column transformations, MinMax scaling, and hyperparameter tuning (grid search) to optimize results within compute constraints

🔗 [WiDS Datathon 2025 | Kaggle Competition Page](https://www.kaggle.com/competitions/widsdatathon2025/overview)

---

## **👩🏽‍💻 Setup & Execution**

**Provide step-by-step instructions so someone else can run your code and reproduce your results. Depending on your setup, include:**

* How to clone the repository
  `git clone https://github.com/ss303/VIR_WiDS_Team-Ganglia.git`
  `cd VIR_WiDS_Team-Ganglia`
* How to install dependencies
  `pip install numpy pandas scikit-learn`
* How to set up the environment
 * Make sure you have python installed
* How to access the dataset(s)
  * Visit the kaggle page, under [data](https://www.kaggle.com/competitions/widsdatathon2025/data) download the dataset
* How to run the notebook or scripts
  * It's a notebook so you can just press the run icon on the side

---

## **🏗️ Project Overview**

**Describe:**

* WiDS Datathon 2025 is a competition that uses machine learning to predict sex and ADHD diagnoses based on brain activity and scio-demographic information. The sigificance of this competition is in the ability to better understand ADHD and neurological diseases.
* The objective of the competition is to predict whether patients have ADHD based on brain activity, this can help with diagnosing ADHD earlier and help with accuracy (avoid misdiagnoses). 
* The impact of this work is that it can lead to better treatment and more targeted treatment. It helps with understanding the different brain waves that are associated with ADHD based on gender. It can help avoid misdiagnoses and reduce the time and resources it takes to diagnose ADHD using ML/AI.

---

## **📊 Data Exploration**

**Describe:**

* The dataset used is the one found in the kaggle competition, it consists of brain activity collected from individuals diagnosed with ADHD and individuals who weren't diagnosed with ADHD. The data is collected through functional MRI and consists of the labels (sex and diagnoses), socio-demographic information, and functional MRI connectome matrices.
* Data exploration and preprocessing approaches
  * We cleaned our data by handling missing values, and standarizing our training data.
* Challenges and assumptions when working with the dataset(s)

** Visualizations:**

* Plots, charts, heatmaps, feature visualizations, sample dataset images

---

## **🧠 Model Development**

**Describe (as applicable):**

* Model(s) used (e.g., CNN with transfer learning, regression models)
  * We used logistic regression as our baseline model and then we used multioutput random forest model as our final submission. Ridge classifer allows us to tackle linear relationships. Then Random Forest allows us to capture more complex patterns. Thus using a stacking classifer will allow us to combine ridge and random forest classfier to get the best performance.
* Feature selection and Hyperparameter tuning strategies
  * For feature selection we removed features that had high correlation to each other and then we used Gridsearch to tune the hyperparameters.
* Training setup (e.g., % of data for training/validation, evaluation metric, baseline performance)

---

## **📈 Results & Key Findings**

**Describe (as applicable):**

* Performance metrics (e.g., Kaggle Leaderboard score, F1-score)
* How your model performed overall

**Potential visualizations to include:**

* Confusion matrix, precision-recall curve, feature importance plot, prediction distribution, outputs from fairness or explainability tools

---

## **🖼️ Impact Narrative**

**Answer the relevant questions below based on your competition:**

**WiDS challenge:**

1. What brain activity patterns are associated with ADHD; are they different between males and females, and, if so, how?
2. How could your work help contribute to ADHD research and/or clinical care?

---

## **🚀 Next Steps & Future Improvements**

**Address the following:**

* What are some of the limitations of your model?
* What would you do differently with more time/resources?
  *Try out more different models, espeically with the new training data set. 
* What additional datasets or techniques would you explore?

---

## **📄 References & Additional Resources**

* n/a

---

